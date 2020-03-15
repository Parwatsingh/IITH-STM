  # IITH Software Transactional Memory (STM) Library
    Mounika, Parwat Singh Anjana, Sathya Peri
    
    This library for provides support Software Transactional Memory (STM) in C++.
    The documentation to use the libraries: [STM Library API](https://github.com/Parwatsingh/IITH-STM/edit/master/STM-Library-API.pdf>

    A recent paper describing the results of the implementation of various 
    algorithms of IITH STM can be found here: [Result-Comparison](https://www.iith.ac.in/~sathya_p/lib_files/Result-Comparison.pdf)

## Compile
    g++ -std=c++14 -g main.cpp txBarrier.cpp -o test -ltbb -lpthread


## Output
    The output is verbose as it prints logs.
    They can be set off by setting DEBUG_LOGS to 0 in txBarrier.h.
    The transactions in barrier keep retrying until they succeed.
    Hence some times, it takes much time to exit the barrier.


## Copyright 2019 Parallel and Distributed Computing Research Lab (PDCRL), IIT Hyderabad, India
    Licensed under the Apache License, Version 2.0 (the "License"); 
    you may not use files in this project except in compliance with the License.
    You may obtain a copy of the License at

      <http://www.apache.org/licenses/LICENSE-2.0>

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an 
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, 
    either express or implied. See the License for the specific 
    language governing permissions and limitations under the License.
