<!--
 Licensed to the Apache Software Foundation (ASF) under one
 or more contributor license agreements.  See the NOTICE file
 distributed with this work for additional information
 regarding copyright ownership.  The ASF licenses this file
 to you under the Apache License, Version 2.0 (the
 "License"); you may not use this file except in compliance
 with the License.  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
-->

## Building
You can build Tephra directly from the latest source code:

```sh
  git clone https://git-wip-us.apache.org/repos/asf/incubator-tephra.git
  cd incubator-tephra
  mvn clean package -fn

  if want to build with Ekstazi: 
  mvn ekstazi:ekstazi -fn

  if you want build with STARTS:
  mvn starts:starts -fn 
```

