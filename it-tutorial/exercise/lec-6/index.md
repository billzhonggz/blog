---
title: Exercises on Lecture 6
date: 2018-04-26 22:49:09
comments: false
---

## Exercises on Lecture 6

> 编写：钟钧儒
>
> 最后修改日期：2018年4月26日
>
> *仅适用于2018春季IT辅导班*
>
> *本文档仅用于参考，不可用于实际测试*
>
> **正确答案以加粗显示**

1. What is Analogue Data?

  a. A continuous representation which roughly describes the actual information.

  b. A discrete representation which precisely describes the actual information.

  **c. A continuous representation which precisely describes the actual information.**

  d. A discrete representation which breaks the information into units and approximates the actual information.

  > 出自PPT原文

  ​

2. What is Digital Data?

  a. A continuous representation which roughly describes the actual information.

  b. A discrete representation which precisely describes the actual information.

  c. A continuous representation which precisely describes the actual information.

  **d. A discrete representation which breaks the information into units and approximates the actual information.**

  > 出自PPT原文

  ​

3. In what way data represents that make the computer available to process?

  a. Represents in images.

  b. Represents in waves.

  c. Represents in particles.

  **d. Represents in binary digits.**

  > 计算机仅能处理二进制数字。很明显数据不能在计算机中被表示为图像、波形或者粒子。

  ​

4. In the following descriptions, which is correct?

  a. The goal to represent data is using as many bits as possible to ensure accuracy.

  > 计算机表示数据的目标是“用最少的数据量准确地表达”，而不是通过暴力增加数据量来达到准确的目的。

  b. Lossless compression will lead to loss of original information.

  > 无损压缩不会损失原始数据

  c. **Lossy compression can be often seen in image and video compression.**

  > 有损压缩常见于图片（JPEG、GIF）和视频（MPEG系列）压缩格式。因为图片和视频的原始数据量都非常大，而通过某些基于人类感受模式的模型可以有效地压缩体积，所以有损压缩在图片和视频的压缩中很常见。

  d. Lossless compression gives up some non-curial information.

  > 无损压缩不会损失任何数据。

  ​

5. In the following statements about text representation, which is correct?

  a. A character set is an approach that a computer displays text.

  > 是数据的表示方法，而不是显示方法。

  **b. ASCII does not include Chinese characters.**

  > ASCII仅包含拉丁字符和其他符号，不包含中文等东亚文字编码。

  c. Unicode does not include Chinese characters.

  > Unicode是ASCII的超集。增加的范围就有CJK文字。

  d. ASCII uses 16 bits to represent a character.

  > ASCII使用8位数表示字符。

  ​

6. In the following statements about audio representation, which is correct?

  **a. Sampling is an approach to represent audio.**

  > 从模拟信号中采样是计算机表示音频的主要（可能是唯一）方法。

  b. MP3 is a lossy compression format.

  > MP3是一种有损、无损结合的压缩格式。

  c. MP3 stands for Moving Picture Experts Group 3 format.

  > MP3意味MPEG 1 Layer 3。

  d. M4V is an audio format.

  > M4V是一种视频格式。系MPEG4中的视频流。

  ​

7. In the following statements about colour representation, which is correct?

  a. A colour is represented by a combination of Red, Black, and White.

  > R、G、B三原色。

  **b. True color uses 8 bits to represent a primary color.**

  c. Resolution is the number of pixels per inch.

  > 据课件，分辨率为图像的尺寸而不是像素密度。但据[维基百科](https://en.wikipedia.org/wiki/Image_resolution)，Resolution可以指图像尺寸和像素密度两种含义。请以课件为准。

  d. A BMP image is a combination of vectors.

  > BMP格式的图片是以像素而不是矢量存储的。一种新的用于网络的图片格式，[SVG](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics)，则是基于矢量的格式。

  ​

8. In the following statements about video representation, which is NOT correct?

  a. A frame in a video is an image.

  b. Frame rate always measures in Frames Per Second.

  **c. Almost all videos are encoded using lossless compression.**

  > 由于视频数据量很大，所以一般使用有损压缩来减少体积。

  d. VLC Media Player is a video player.

### 接下来

[返回上一层](../../) | [下载PDF版](Exercises-on-Lecture-6.pdf)