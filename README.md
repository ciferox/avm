# `avm` - Adone Version Manager

Complete Node.js and ADONE version management.

## Installation

    $ curl -L https://adone.io/dist/avm.sh | sudo bash -s install

## Usage

Help can be obtained from `avm --help`.

    Usage: avm [options] [COMMAND] [args]
    avm install                         Install avm
    avm update                          Actually, the same as install
    avm rm                              Remove avm
    avm [--clean] bootstrap             Install latest node.js and adone versions
    Node.js management:
      avm node ls                       Display installed node.js versions
      avm node ls-remote                Display available to install node.js versions
      avm node latest                   Display latest node.js version
      avm node stable                   Display stable node.js version
      avm node update                   The same as force installing the latest version
      avm node [--force] download <version>
                                        Download node.js version
      avm node [--force] activate <version>
                                        Activate node.js version
      avm node [--force] install <version>
                                        Download and activate node.js version
      avm node rm <version>             Remove installed node.js version
      avm node [--build] build <version>
               [--user user]            Build node.js version from sources and upload it to adone.io
               [--pass pass]
    Adone management:
      avm adone ls                      Display installed adone versions
      avm adone ls-remote               Display available to install adone versions
      avm adone latest                  Display latest adone version
      avm adone stable                  Display stable adone version
      avm adone update                  The same as force installing the latest version
      avm adone [--force] download <version>
                                        Download adone version
      avm adone [--force] activate <version>
                                        Activate downloaded adone version
      avm adone [--force] install <version>
                                        Download and activate adone version
      avm adone rm <version>            Remove installed adone version
      avm adone link <name>             Create a symbolic link to adone binary
      avm adone rm-link <name>          Remove a symbolic link to adone binary
    Adone dependencies:
      avm deps                          List all the dependencies
      avm deps install                  Install all the dependencies
      avm deps install <package> [<package> ...]
                                        Install particular dependencies
    Options:
      -V, --version     Output current version of avm
      -h, --help        Display this help information
      -d, --download    Only download
      -f, --force       Force download/activate
      -c, --clean       Remove avm directory
      -b, --build       Just build, do not upload
      --user            Username for uploading
      --pass            Password for uploading
      
## License

Copyright 2017 Ciferox Inc. <adone@ciferox.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
