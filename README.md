# 1 Overview

ComPDFKit, a software development kit (SDK), consists of PDF SDK and PDF Conversion SDK. With ComPDFKit, even developers with limited knowledge of PDF can quickly integrate professional PDF functions with just a few lines of code on multiple platforms. And we will introduce ComPDFKit PDF SDK for iOS here.

ComPDFKit PDF SDK for iOS is a robust PDF library for developers who need to develop applications on iOS, which offers powerful Objective-C APIs for quickly viewing, annotating, editing, and creating PDFs. It is feature-rich and battle-tested, making PDF files process and manipulation easier and faster for iOS devices.

## 1.1 ComPDFKit PDF SDK

ComPDFKit PDF SDK consists of two elements as shown in the following picture.

![Alt text](https://github.com/ComPDFKit/PDF-SDK-iOS/blob/main/image-ios/1.png)

The two elements for ComPDFKit PDF SDK:

- **PDF Core API**

The Core API can be used independently for document rendering, analysis, text extraction, text search, form filling, password security, annotation creation and manipulation, and much more.

- **PDF View**

The PDF View is a utility class that provides the functionality for developers to interact with rendering PDF documents per their requirements. The View Control provides fast and high-quality rendering, zooming, scrolling, and page navigation features. The View Control is derived from platform-related viewer classes (e.g. `UIView` on iOS) and allows for extension to accommodate specific user needs.

## 1.2 Key Features

**Viewer** component offers:

- Standard page display modes, including Scrolling, Double page, Crop mode, and Cover mode.
- Navigation with thumbnails, outlines, and bookmarks.
- Text search & selection.
- Zoom in and out & Fit-page.
- Switch between different themes, including Dark mode, Sepia mode, Reseda mode, and Custom color mode.
- Text reflow.

**Annotations** component offers:

- Create, edit and remove annotations, including Note, Link, Freetext, Line, Square, Circle, Highlight, Underline, Squiggly, Strikeout, Stamp, Ink, Sound
- Support for annotation appearances.
- Import and export annotations to/from XFDF.
- Support for annotation flattening.
- Predefine annotations.

**Forms** component offers:

- Create, edit and remove form fields, including Push Button, Check Box, Radio Button, Text Field, Combo Box, List Box, and Signature.
- Fill PDF Forms.
- Support for PDF form flattening.

**Document editor** component offers:

- PDF manipulation, including Split pages, Extract pages, and Merge pages.
- Page edit, including Delete pages, Insert pages, Crop pages, Move pages, Rotate pages, Replace pages, and Exchange pages.
- Document information setting.
- Extract images.

**Security** component offers:

- Encrypt and decrypt PDFs, including Permission setting and Password protected.
- Create, edit, and remove watermark.
- Redact content including images, text, and vector graphics.
- Create, edit, and remove header & footer, including dates, page numbers, document name, author name, and chapter name.
- Create, edit, and remove bates numbers.
- Create, edit, and remove background that can be a solid color or an image.

**Conversion** component offers:

- PDF to PDF/A.

## 1.3 License

ComPDFKit PDF SDK is a commercial SDK, which requires a license to grant developer permission to release their apps. Each license is only valid for one bundle ID in development mode. Other flexible licensing options are also supported, please contact [our marketing team](mailto:support@compdf.com) to know more.  However, any documents, sample code, or source code distribution from the released package of ComPDFKit to any third party is prohibited.

# 2 Get Started

It is easy to embed ComPDFKit in your iOS app with a few lines of Objective-C code. Takes just a few minutes and gets started. 

The following sections introduce the structure of the installation package, how to run a demo, and how to make an iOS app in Objective-C with ComPDFKit PDF SDK. 

## 2.1 Requirements

ComPDFKit requires the latest stable version of Xcode available at the time the release was made. This is a hard requirement, as each version of Xcode is bundled with a specific version of the iOS Base SDK, which often defines how UIKit and various other frameworks behave. 

- iOS 10.0 or higher.
- Xcode 12.0 or newer for Objective-C or Swift.

## 2.2 iOS Package Structure

The package of ComPDFKit PDF SDK for iOS includes the following files as shown in Figure 2-1:

- **ComPDFKit.xcframework** - Include the ComPDFKit dynamic library (arm64_armv7, x86_64-simulator) and associated header files.
- **PDFViewer** - A folder containing iOS sample projects.
- **PDFViewer-Swift** - A folder containing Swift iOS sample projects.
- **api_reference_ios** - API reference.
- **developer_guide_ios.pdf** - Developer guide.
- **release_notes.txt** - Release information.
- **legal.txt** - Legal and copyright information.

![Alt text](https://github.com/ComPDFKit/PDF-SDK-iOS/blob/main/image-ios/2-1.png)

<p align="center">
Figure 2-1
</p>

## 2.3 How to run a demo

ComPDFKit PDF SDK for iOS provides one demo in Objective-C for developers to learn how to call the SDK on iOS. You can find them in the ***"PDFViewer"*** folder. In this guide, it takes the "Objective-C" demo as an example to show how to run it in Xcode.

1. Double-click the ***"PDFViewer.xcodeproj"*** found in the ***"PDFViewer"*** folder to open the demo in Xcode.

2. Click on ***"Product -> Run"*** to run the demo on an iOS device. In this guide, an iPhone 7 Plus device will be used as an example. After building the demo successfully, on the start screen, click the ***"PDF32000_2008.pdf"*** document, and then it will be opened and displayed.

![Alt text](https://github.com/ComPDFKit/PDF-SDK-iOS/blob/main/image-ios/2-1-1.png)
