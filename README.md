# 《Windows Subsystem for Linux 2 (WSL 2) Tips, Tricks, and Techniques》Learning Notes



## 1. Profiles

![Redis 4.x Cookbook](assets/cover.png)

|    **Title**    | **Windows Subsystem for Linux 2 (WSL 2) Tips, Tricks, and Techniques** [ISBN: 9781800562448] |
| :-------------: | :----------------------------------------------------------: |
|   **Author**    |                       **Stuart Leeks**                       |
| **Publication** |                      **Packt, 2020.10**                      |
|    **Pages**    |                           **246**                            |

> **Introduction**
>
> Windows Subsystem for Linux (WSL) allows you to run native Linux tools alongside traditional Windows applications. Whether you’re developing applications across multiple operating systems or looking to add more tools to your Windows environment, WSL offers endless possibilities. You’ll start by understanding what WSL is and learn how to install and configure WSL along with different Linux distros. Next, you'll learn techniques that allow you to work across both Windows and Linux environments. You’ll discover how to install and customize the new Windows Terminal. We'll also show you how to work with code in WSL using Visual Studio Code (VS Code). In addition to this, you’ll explore how to work with containers with Docker and Kubernetes, and how to containerize a development environment using VS Code. While Microsoft has announced support for GPU and GUI applications in an upcoming release of WSL, at the time of writing these features are either not available or only in early preview releases. This book focuses on the stable, released features of WSL and giving you a solid understanding of the amazing techniques that you can use with WSL today. By the end of this book, you’ll be able to configure WSL and Windows Terminal to suit your preferences, and productively use Visual Studio Code for developing applications with WSL.



## 2. Outlines

Status available：:heavy_check_mark: (Completed) | :hourglass_flowing_sand: (Working) | :no_entry: (Not Started) | :orange_book: (Finish reading)

| No.  |                        Chapter Title                         |          Status          |
| :--: | :----------------------------------------------------------: | :----------------------: |
| Ch01 | [Introduction to the Windows Subsystem for Linux](./Ch01.md) |    :heavy_check_mark:    |
| Ch02 | [Installing and Configuring the Windows Subsystem for Linux](./Ch02.md) | :hourglass_flowing_sand: |
| Ch03 |      [Getting Started with Windows Terminal](./Ch03.md)      |        :no_entry:        |
| Ch04 |        [Windows to Linux Interoperability](./Ch04.md)        |        :no_entry:        |
| Ch05 |        [Linux to Windows Interoperability](./Ch05.md)        |        :no_entry:        |
| Ch06 |       [Getting More from Windows Terminal](./Ch06.md)        |        :no_entry:        |
| Ch07 |         [Working with Containers in WSL](./Ch07.md)          |        :no_entry:        |
| Ch08 |            [Working with WSL Distros](./Ch08.md)             |        :no_entry:        |
| Ch09 |           [Visual Studio Code and WSL](./Ch09.md)            |        :no_entry:        |
| Ch10 |        [Visual Studio Code and Containers](./Ch10.md)        |        :no_entry:        |
| Ch11 |    [Productivity Tips with Command-Line Tools](./Ch11.md)    |        :no_entry:        |



Powershell script for generating markdown files in batch:

```powershell
# Create 11 empty markdown files named Ch##.md:
for($i=1; $i -le 11; $i=$i+1){ New-Item -Name "Ch$('{0:d2}' -f $i).md"; }
```

 
