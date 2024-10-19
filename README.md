## pe-carver

Carves EXEs from given data files, using intelligent carving based upon PE headers.

Updated for Python 3 by digitalsleuth

## Usage

```
usage: pe-carver [-h] -f <input-file> -o <output-folder> [-l <logfile-name>] [--min #] [--max #] [--verbose] [-v]

pe-carver v2.0

optional arguments:
  -h, --help            show this help message and exit
  -f <input-file>, --file <input-file>
                        File to carve, full path
  -o <output-folder>, --output <output-folder>
                        Output folder, full path
  -l <logfile-name>, --log <logfile-name>
                        Log file name, full path
  --min #               Minimum EXE size in bytes, default 10000
  --max #               Maximum EXE size in bytes, default 2000000
  --verbose             Verbose - print status to stdout
  -v                    show program's version number and exit
  ```

## Copyright and license

Copyright 2013 Brian Baskin

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
