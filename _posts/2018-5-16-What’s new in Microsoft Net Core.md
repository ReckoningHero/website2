---
layout: post
title: What’s new in Microsoft .Net Core?
summary: .Net Core 3 will debut in 2019, with the beta expected later this year

---
---

Microsoft’s .Net Core, a cross-platform implementation of the company’s .Net development platform, is being readied for its 2.1 release, featuring improvements to build time performance and tools deployment.

And Microsoft expects to ship .Net Core 3 in 2019, with the first beta expected later in 2018.


## Next version: The features planned for .Net Core 3
New and existing Windows applications will be able to run on .Net Core Version 3, with support offered for Windows Forms, Windows Presentation Foundation, and Universal Windows Platform XAML.

Running desktop apps on .Net Core 3 will offer performance improvements, Microsoft says. Windows desktop will be supported through a set of Windows-specific “Windows Desktop Packs.”

Other capabilities of .Net Core 3 are expected to include:

Windows desktop developers will be able to use the .Net Core deployment model. When a new .Net Core version is released, applications can be updated one app on a PC at a time, without concern for affecting other applications. .Net Core releases are installed in new directories and are not used by other applications. When maximum isolation is required, .Net Core can be deployed with an application. Tools are being developed to bundle an application and .Net Core as a single executable.
Support for .Net Core command-line tools and SDK-style projects in Visual Studio.
Net Core, for web and cloud applications, will continue to be released in parallel with .Net Core. A new version of .Net Standard, providing APIs for .Net implementations, will released as well.

## Coming soon: What’s new in .Net Core 2.1
The open source .Net Core 2.1’s production release expected by summer 2018.

Application-building performance will be much better than it was with the 2.0 and 1.0 versions of .Net Core, Microsoft promises. This is particularly true for incremental builds.


Improvements apply to dotnetbuild on the command line and Visual Studio builds. As part of its build enhancements, Microsoft has improved CLI and MSBuild tools for faster performance.

Other improvements envisioned for .Net Core 2.1 include:

A new deployment and extensibility mechanism for tools, referred to as .Net Core global tools. It replaces .Net CLI Tools. The experience will be similar to Node global tools, reusing the same syntax. Microsoft anticipates a new ecosystem arising for .Net tools.
A smaller runtime install.
The availability of the SignalR library for real-time web functionality, in ASP.Net Core 2.1. A companion to .Net Core, ASP.Net Core is a framework for building internet-connected applications. HTTPS is also on by default in ASP.Net Core 2.1.
To handle outgoing network requests, a rewritten HttpClient handler promising two to ten times the performance.
A set of types, including the Span <T> type (pronounced “span of tee”), providing a uniform representation of memory from multiple sources, including stack allocation and native code. These types are expected initially to help with performance-critical situations and then become a replacement for arrays as a mechanism for handling large blocks of data. One type, Tensor <T>, is specific to machine learning.
For compatibility with .Net Framework, the Windows Compatibility Pack. It offers access to an additional 20,000 APIs compared to what has been available in .Net Core. Released in a beta version in November, the pack offers APIs such as System.Drawing, EventLog, and Windows Services.
The API Analyzer tool, to ensure developers do not only depend on Windows APIs.
Support for applications on later runtime versions in the same major version range. For example, a .Net Core 2.0 application could run on .Net Core 2.1.
Crypto improvements, including support for signing NuGet packages.
