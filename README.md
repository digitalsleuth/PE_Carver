## PE_Carver

Carves EXEs from given data files, using intelligent carving based upon PE headers.

As seen in SANS 508 :)

## Usage

```
usage: pe_carve.py [-h] -f FILE -o OUTPUT [--log LOG]

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  Raw file to carve
  -o OUTPUT, --output OUTPUT
                        Output folder for extracted files
  --log LOG             Log output file
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
