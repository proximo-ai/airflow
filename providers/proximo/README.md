<!--
 Licensed to the Apache Software Foundation (ASF) under one
 or more contributor license agreements.  See the NOTICE file
 distributed with this work for additional information
 regarding copyright ownership.  The ASF licenses this file
 to you under the Apache License, Version 2.0 (the
 "License"); you may not use this file except in compliance
 with the License.  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing,
 software distributed under the License is distributed on an
 "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
 KIND, either express or implied.  See the License for the
 specific language governing permissions and limitations
 under the License.
 -->


# Package apache-airflow-providers-proximo

Release: 2020.5.20

**Table of contents**

- [Backport package](#backport-package)
- [Installation](#installation)
- [Compatibility](#compatibility)
- [PIP requirements](#pip-requirements)
- [Provider class summary](#provider-class-summary)
    - [Operators](#operators)
    - [Sensors](#sensors)
    - [Hooks](#hooks)
- [Releases](#releases)
    - [Release 2020.5.20](#release-2020520)


**Only Python 3.6+ is supported for this package.**

While Airflow 1.10.* continues to support Python 2.7+ - you need to upgrade python to 3.6+ if you
want to use this backport package.



## Installation

You can install this package on top of an existing airflow 1.10.* installation via
`pip install apache-airflow-providers-proximo`

## Compatibility

For full compatibility and test status of the backport packages check
[Airflow Backport Package Compatibility](https://cwiki.apache.org/confluence/display/AIRFLOW/Backported+providers+packages+for+Airflow+1.10.*+series)

## PIP requirements

| PIP package   | Version required   |
|:--------------|:-------------------|
|               |                    |

# Provider class summary

All classes in Airflow 2.0 are in `airflow.providers.proximo` package.


## Operators



| Airflow 2.0 operators: `airflow.providers.proximo` package                                                                                         |
|:---------------------------------------------------------------------------------------------------------------------------------------------------|
| [operators.proximo.ProximoOperator](https://github.com/proximo-ai/airflow/blob/master/providers/proximo/operators/proximo.py)                       | 
| [operators.proximo_check.ProximoCheckOperator](https://github.com/proximo-ai/airflow/blob/master/providers/proximo/operators/proximo_check.py)      |



## Sensors



| Airflow 2.0 sensors: `airflow.providers.proximo` package                                                                         | 
|:---------------------------------------------------------------------------------------------------------------------------------|
| [sensors.proximo.ProximoSensor](https://github.com/apache/proximo-ai/airflow/blob/master/providers/proximo/sensors/proximo.py)          |



## Hooks



| Airflow 2.0 hooks: `airflow.providers.proximo` package                                                                              |
|:-----------------------------------------------------------------------------------------------------------------------------------|
| [hooks.proximo.ProximoHook](https://github.com/proximo-ai/airflow/blob/master/providers/proximo/hooks/proximo.py)                  |


## Releases

### Release 2020.5.20

| Commit                                                                                             | Committed   | Subject                                                                                                                                                            |
|:---------------------------------------------------------------------------------------------------|:------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [12c5e5d8a](https://github.com/proximo-ai/airflow/commit/12c5e5d8ae25fa633efe63ccf4db389e2b796d79) | 2020-05-17  | Prepare release candidate for initial version packages (#8891)                                                                                                     |
