# ZoomableImageView #

Simple Android ImageView that enables dragging and zooming. Compatible with API 7 (Android 2.1).

## Usage

Please check out the [example project](https://github.com/jeremiemartinez/ZoomableImageView/tree/master/zoomableimageview_examples).

If you need more technical information, you can refer to the javadoc I wrote in the [ZoomableImageView class](https://github.com/jeremiemartinez/ZoomableImageView/tree/master/zoomableimageview_library/src/com/github/jeremiemartinez/zoomable/ZoomableImageView.java).

### How to integrate it ?

#### Eclipse
Since ZoomableImageView is an apklib, you have to [download it](https://github.com/jeremiemartinez/ZoomableImageView/archive/master.zip) and import the **zoomableimageview_library** folder in your Eclipse.

Then you need to go to Properties > Android in your project and add ZoomableImageView as a Library.

#### Maven

``` xml
<dependency>
   <groupId>com.github.jeremiemartinez</groupId>
   <artifactId>zoomableimageview</artifactId>
   <type>apklib</type>
   <version>1.0</version>
</dependency>
```

### How to use it ?

#### Layout:

``` xml
  <com.github.jeremiemartinez.zoomable.ZoomableImageView
  android:id="@+id/imageView"
  android:layout_height="match_parent"
  android:layout_width="match_parent" />
```

## Developed by
  * Jeremie Martinez - [jeremiemartinez@gmail.com](mailto:jeremiemartinez@gmail.com)
    
Inspired by Mike Ortiz [TouchImageView](https://github.com/MikeOrtiz/TouchImageView)

    
## Licence
    
Copyright 2012-2013 - Jeremie Martinez ([jeremiemartinez@gmail.com](mailto:jeremiemartinez@gmail.com))
    
Licensed under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy of
the License at

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
    
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations under
the License.
