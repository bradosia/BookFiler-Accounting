# Bookfiler™ Accounting

## Features

* Very fast categorizing expenses
* Multi-user support (clients have a server mode)
* double-entry bookkeeping system with optional abstraction for categorizing expenses

## Monetization

* Core modules are free
* New modules will be sold for $1, no upgrade option, no warranty

# Formats

| Bank | Format | Description |
|:-- |:-- |:-- |
|Chase|csv|universal format with moderate data. Transaction text info displayed as single description |
|Chase|qbo|best format for most information. separates description into transaction name and memo fields|
|Chase|qfx|same as above|
|Chase|qif|Very short form format. Descriptions are truncated|
|BoA|csv|has an extra address field that simply is parsed from description. Has a reference ID|
|BoA|qfx|xml formatted with basic transaction info and some account meta data|
|BoA|qif|short form with date year represented with 2 digits|
|BoA|qif|short form with date year represented with 4 digits|

# Competitors

* https://help.sap.com/viewer/2754875d2d2a403f95e58a41a9c7d6de/1905/en-US/2ce2afc4722d1014877689c0aab386e5.html

# Technical
Dear IMGUI load images:
* https://github.com/ocornut/imgui/wiki/Image-Loading-and-Displaying-Examples
* https://www.khronos.org/registry/OpenGL-Refpages/gl4/html/glTexImage2D.xhtml
* https://tpgit.github.io/Leptonica/struct_pix.html#aef4c9107abdca8b948d1a0e61dac8acc

OCR
* https://ub-mannheim.github.io/tesseract/a01758.html#ga0e4065c20b142d69a2324ee0c74ae0b0
* https://ub-mannheim.github.io/tesseract/a02893.html#ac350ee2b121c4bf1f625b1606a859d0a

HOCR
* http://kba.cloud/hocr-spec/1.2/#sec-ocr_line

PDF:
* http://podofo.sourceforge.net/doc/html/namespacePoDoFo.html
* https://github.com/mariusmuja/mupdf/blob/master/doc/example.c

C++
* http://www.cplusplus.com/reference/memory/dynamic_pointer_cast/

Shared Memory:
* https://www.boost.org/doc/libs/1_63_0/doc/html/interprocess/quick_guide.html

Processes:
* https://www.boost.org/doc/libs/develop/doc/html/boost_process/tutorial.html#boost_process.tutorial.launch_mode

SVG:
* https://www.boost.org/doc/libs/1_72_0/libs/geometry/doc/html/geometry/reference/io/svg/svg_mapper.html

IMGUI Documents:
* http://docs.ros.org/kinetic/api/librealsense2/html/structImFont.html
