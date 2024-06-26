﻿
**演示地址:**[http://pichome.oaooa.com](http://pichome.oaooa.com/)

PicHome是一款功能强大的开源网盘程序，它不仅能高效管理各类文件，还在图像和媒体文件管理方面表现出色。其亮点包括强大的文件共享功能和先进的AI辅助管理工具，为用户提供了便捷、智能的文件管理体验。

![1.jpg](https://imgc.cc/2024/04/29/662f1116e65a8.jpg)

---

**开发背景**
在数字化时代背景下，图像、音视频等媒体文件已成为信息传递的核心载体，其重要性不断攀升。然而，传统网盘在处理这类文件时的管理方式逐渐显得力不从心。正是基于这一现实需求，PicHome应时而生，致力于提供一种创新、高效的媒体文件管理策略。

**技术基础**
- 开发语言：PHP
- 数据库：MYSQL
- 开源协议：AGPL V2

---
### 功能特性

**网盘基础功能：与传统网盘的优势对比**

1. **多样化的列表模式**
   - 传统网盘：传统网盘通常仅提供列表和网格两种视图。
   - PicHome：提供包括瀑布流、自适应布局、网格、列表、双排列表和详细视图在内的多种模式，以适应不同用户的视觉和操作体验。
![2.jpg](https://imgc.cc/2024/04/29/662f111360fa0.jpg)

2. **定制化的文件信息展示**
   - 传统网盘：信息展示固定，通常只显示图标、文件名和后缀名。
   - PicHome：允许用户根据需要自定义显示文件名、后缀名、标签、文件大小、图像尺寸、视频时长和添加时间等丰富信息。
![3.jpg](https://imgc.cc/2024/04/29/662f111320055.jpg)

3. **增强的文件快速预览功能**
   - 传统网盘：需要打开文件才能查看内容。
   - PicHome：通过提供足够大的缩略图，使得用户在没有打开文件的情况下就能快速识别和选择所需文件。音视频文件甚至可以在列表中直接预览，快进播放。极大提升了查询效率。


4. **先进的标签化文件管理**
   - 传统网盘：大多不支持或仅提供基础的标签管理功能。
   - PicHome：支持自动获取图片的颜色、形状等属性，以及音视频的时长等信息，并允许用户添加二级标签、文件描述和评分，从而实现多维度、深度的文件管理。
![4.jpg](https://imgc.cc/2024/04/29/662f111345222.jpg)

5. **自定义封面图与预览图**
   - 传统网盘：文件以图标形式展示，图片和视频以自动生成的固定封面展示。
   - PicHome：允许用户为任意文件自定义封面，这对于设计文件、压缩包等复杂文件来说，可以更全面地展示文件内容。
![5.jpg](https://imgc.cc/2024/04/29/662f11111cec3.jpg)

6. **多预览图功能**
   - 传统网盘：传统网盘中一般不支持多预览图，并且不支持预览的文件也无法预览。
   - PicHome：不支持预览的文件可自定义封面与预览图，还支持多预览图的方式，比如在设计图、模型文件、压缩包等文件中，单张预览图无法表达文件全貌时，可提供多张预览图，便于用户更全面地了解文件全貌。 
![6.jpg](https://imgc.cc/2024/04/29/662f1111d7f53.jpg)

7. **多库管理功能**
   - 传统网盘：通常只提供一个统一的文件管理空间。
   - PicHome：支持创建多个网盘库，根据文件类型和业务需求进行分类存储和分配管理权限，提高了文件管理的灵活性和效率。
![7.jpg](https://imgc.cc/2024/04/29/662f1113b7156.jpg)

**文件共享功能：重塑文件共享边界**

PicHome的文件共享功能强大且灵活，它不仅支持整个库的共享，还允许用户创建个性化的展示网页，甚至构建完整的资料分享展示网站。
- **共享整个库**：用户可以选择性地共享整个库给朋友、同事或客户。库的展示样式可以个性化设置，优化访问者的浏览体验。
![8.jpg](https://imgc.cc/2024/04/29/662f1114cdd6e.jpg)

- **共享展示网页**：PicHome 的单页功能允许用户无需编写代码，通过拖拽模块快速制作个性化的展示网页。用户可以自由组合轮播图、文件推荐、富文本、常见问题和链接等模块，打造精美的展示页面。
![9.jpg](https://imgc.cc/2024/04/29/662f1116bb5ef.jpg)

- **组织结构化的共享网站**：PicHome 可以将共享文件、整库和单页等元素组织成一个完整的网站。这样，用户可以快速建立个人家庭媒体资料库、团队共享资料库或企业文件资料库网站。
![10.jpg](https://imgc.cc/2024/04/29/662f11176c443.jpg)

---

**AI辅助管理：智能化文件标注与管理**

文件的分类和标注一直是文件管理中的挑战，需要管理人员投入大量时间和精力。幸运的是，如今AI大模型的出现为这项工作提供了解决方案。PicHome 将全面整合AI智能功能，以提升文件管理效率。目前，PicHome 已经实现了以下AI辅助功能：

1. **AI修改文件名**：自动识别文件内容并生成更有意义的文件名，提高文件查找效率。

2. **AI打标签**：根据文件内容自动添加标签，帮助用户更快速地分类和检索文件。

3. **AI写描述**：智能生成文件描述，让用户了解文件内容，无需手动编辑。

4. **AI批量标注**：一次性对多个文件进行标注，减少人工操作。

5. **AI文件问答**：回答用户关于文件的问题，提供更智能的文件管理服务。

 在PicHome中，各项文件标注功能通过自定义Prompt来实现。不同的Prompt描述可以引导AI生成不同方向的结果，从而实现针对不同行业、不同类型文件的精准标注。管理员可以在后台自定义设置多条Prompt，并在管理界面中方便地选择采用哪个Prompt来进行文件标注。
![11.jpg](https://imgc.cc/2024/04/29/662f11162e2dd.jpg)

AI对各文件类型支持陆续增加中，目前已经支持的文件类型：
- [x] 图片
- [ ] 视频
- [ ] 文档

 PicHome还将陆续提供更多能够对接的在线大模型，以及对接私有化大模型的方案，以满足不同用户的需求。

---

**支持格式**

 任意格式的文件都可以上传导入，支持大多数常见格式的预览，支持图片水印保护源文件。

**图像**

   svg  png jpg jpeg jpe webp  jfif ico heic gif eps bmp tga hdr exr dds ppm pnm pgm pdd pcx pbm pam mpo mng miff jpx jps jpf jpc jp2 j2k j2c dib cur cin  tif  wmf  emf tiff

**源文件**

   psd ai

**音频**

   wav ogg mp3 m4a flac aac ape aiff amr

**视频**

   wmv webm mp4 mov m4v avi ts swf rmvb rm mkv flv vob trp sct ogv mxf mpg m2ts f4v dv dcr asf 3g2p

**RAW**

   3fr arw cr2 cr3 crw dng erf mrw nef nrw orf otf pef raf raw rw2 sr2 srw x3f

**办公**

   xlsx xls pptx ppt pdf docx  doc pdf txt rtf odt htm html mht pps ppsx odp ods csv

**压缩包**

 zip rar

---

**丰富使用场景**

 可以应用于电商，游戏，设计，开发，企事业，学校，实验室，媒体，演艺机构等类型的个人，团队，企业业务中

1. 作为普通网盘使用
2. 创建素材共享库
3. 创建文件发布网站
4. 实现 Eagle 素材库多端展示
5. 实现 Billfish 素材库多端展示
6. 实现普通文件夹多端展示
7. 建立企业知识库
8. 建立代理商，分销商，分公司产品资料共享平台
9. 建立商品素材，商品图共享平台
10. 建立企业图库平台
11. 建立团队灵感库
12. 建立团队标准库
13. ......


---

## **PicHome 使用了解

**PicHome** 分为后台和前台两个部分，各自担任不同的角色。

### **后台功能**

- 后台主要用于系统配置，定位类似于“系统开发”人员使用。
- 只是这个“开发”工作并不需要代码知识，只需通过配置与拖拽，就可以实现各种个性化需求。
- 后台就像一个无代码网页设计器，能够在无需编程的情况下配置出各种个性化的页面效果。
- 如果你对 **PicHome** 的后台配置熟悉了，不但可以搭建出满足自身各种需求的文件系统，甚至可以帮助他人或者企业搭建各类定制化需求的文件资源共享平台。

### **前台功能**

- 前台是平时正常使用的界面，用于展示数据和进行日常管理。
- 所有的网盘管理和文件管理都在前台门户和个人中心中进行。
- 作为使用人员时，你只需在前台的门户中对展示出来的数据进行查询和检索。
- 需要管理网盘文件时，只需进入个人中心，对不同的库进行文件管理，而无需进入后台。
- **PicHome** 的前台操作简单易上手，让你轻松管理文件和数据。

---

