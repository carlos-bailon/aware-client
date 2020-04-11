AWARE Framework Android Client
======================

AWARE is an Android framework dedicated to instrument, infer, log and share mobile context information,
for application developers, researchers and smartphone users. AWARE captures hardware-, software-, and 
human-based data. It encapsulates analysis, machine learning and simplifies conducting user studies 
in naturalistic and laboratory settings.

The platform is scalable with plugins and can be integrated with other platforms using JSON, MQTT or MySQL.


Extra features
===============

* [ESM Flexible Plugin](https://github.com/carlos-bailon/com.aware.plugin.esm.flexible)
* New ESM type: *ESM_ScaleImage*
* New utils class *ESM_ImageUtils* to retrieve remote images and convert to bitmap
* New parameters added to ESM questions: *completion time*, *cancel button text* and *class*
* New argument in *queueESM* method to indicate that the ESM has been manually triggered and does not require notification (*isManual*)
* Added verification of past schedules not triggered in time to *Scheduler* class

Open-source (Apache 2.0)
========================

Copyright (c) 2011 AWARE Mobile Context Instrumentation Middleware/Framework 
![https://www.awareframework.com](http://www.awareframework.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at 
http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
