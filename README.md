# base32

## ビルド

    $ rebar3 compile

## 利用

```erlang
$ rebar3 shell
1> base32:decode(crockford, <<"AXQQEB10D5T20WK5C5P6RY90EXQQ4TVK44">>).
<<"Wow, it really works!">>
2> base32:encode(crockford, <<"Wow, it really works!">>).
<<"AXQQEB10D5T20WK5C5P6RY90EXQQ4TVK44">>
```

## ライセンス

```
Copyright 2020, Shiguredo Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
