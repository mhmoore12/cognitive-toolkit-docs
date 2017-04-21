Title:   The Microsoft Cognitive Toolkit
Author:    chrisbasoglu
ms.author:   cbasoglu
Date:    04/06/2017
ms.date:   04/06/2017
ms.topic:   landing-page
ms.service:  Cognitive-services
ms.devlang:   NA

# The Microsoft Cognitive Toolkit


The Microsoft Cognitive Toolkit - CNTK - is a unified deep-learning toolkit by Microsoft Research. [This video](https://youtu.be/9gDDO5ldT-4) provides a high-level view of the toolkit. 

The latest release of the Microsoft Cognitive Toolkit 2.0 is RC1 (release candidate 1). If you are a previous user of the toolkit, see [this page](https://github.com/Microsoft/CNTK/wiki/Breaking-changes-in-Master-compared-to-beta15) for more information about (breaking) changes in this release.

It can be included as a library in your Python or C++ programs, or used as a standalone machine learning tool through its own model description language (BrainScript). CNTK supports 64-bit Linux or 64-bit Windows operating systems. To install you can either choose pre-compiled binary packages, or compile the Toolkit from the source provided in Github.

Here are a few pages to get started:
* [Setting up CNTK on your machine](./Setup-CNTK-on-your-machine)
* [[Tutorials, Examples, etc..]]
  * Try the [tutorials on Azure Notebooks](https://notebooks.azure.com/CNTK/libraries/tutorials) with **pre-installed** CNTK 
* [The CNTK Library APIs](./CNTK-Library-API)
  * [Using CNTK from Python](https://www.cntk.ai/pythondocs)
  * [Using CNTK from C++](https://github.com/Microsoft/CNTK/wiki/CNTK-Library-API#c-api)
* CNTK as a machine learning tool through [BrainScript](./Using-CNTK-with-BrainScript)
* [How to contribute to CNTK](./Contributing-to-CNTK)
* Give us feedback through these [channels](https://github.com/Microsoft/CNTK/wiki/Feedback-Channels).

***2017-03-31.* CNTK 2.0 Release Candidate 1**  
With Release Candidate 1 the Microsoft Cognitive Toolkit enters the final set of enhancements before release of the production version of CNTK 2.0. 

Highlights:
* The release candidate contains [all changes and improvements introduced in CNTK 2.0 during beta phase](https://github.com/Microsoft/CNTK/wiki/CNTK-2.0-Beta-Highlights).
* Enables Caffe-converted pretrained models on image classification including AlexNet, ResNet, VGG and BN-Inception. 
* Slice now supports multiple-axis slicing.
* Improves performance and memory footprint
* Improvements in the [device selection API](https://github.com/Microsoft/CNTK/wiki/CNTK_2_0_RC_1_Release_Notes).
* New Python [model debugging functions](https://www.cntk.ai/pythondocs/cntk.debugging.html#module-cntk.debugging.debug).
* Improvements in Python and C# API. See the [release notes](https://github.com/Microsoft/CNTK/wiki/CNTK_2_0_RC_1_Release_Notes) for detailed description.
* New file names for [CNTK libraries and dlls](https://github.com/Microsoft/CNTK/wiki/CNTK-Shared-Libraries-Naming-Format).

The [release notes](https://github.com/Microsoft/CNTK/wiki/CNTK_2_0_RC_1_Release_Notes) contain an overview. 
Get the release from the [CNTK Releases Page](https://github.com/Microsoft/CNTK/releases).

***2017-03-16.* V 2.0 Beta 15 Release available at Docker Hub**  
CNTK V 2.0 Beta 15 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](https://github.com/Microsoft/CNTK/wiki/CNTK-Docker-Containers).

***2017-03-15.* V 2.0 Beta 15 Release**  
Highlights of this Release:
* In addition to pre-existing python support, added support for TensorBoard output in BrainScript. [Read more here](https://github.com/Microsoft/CNTK/wiki/Using-TensorBoard-for-Visualization).
* Learners can now be implemented in pure Python by means of `UserLearners`. [Read more here](https://www.cntk.ai/pythondocs/extend.html#user-learners).
* New debugging helpers: `dump_function()`, `dump_signature()`.
* Tensors can be indexed using advanced indexing. E.g. `x[[0,2,3]]` would return a tensor that contains the first, third and fourth element of the first axis.
* Significant updates in the [Layers Library](https://www.cntk.ai/pythondocs/layerref.html) of Python API. See [Release Notes](https://github.com/Microsoft/CNTK/wiki/CNTK_2_0_beta_15_Release_Notes) for detailed description.
* Updates and [new examples](https://github.com/Microsoft/CNTK/wiki/CNTK-Eval-Examples#examples-for-evaluating-multiple-requests-in-parallel) in C# API.
* Various bug fixes.

See more in the [Release Notes](https://github.com/Microsoft/CNTK/wiki/CNTK_2_0_beta_15_Release_Notes).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

***2017-02-28.* V 2.0 Beta 12 Release available at Docker Hub**  
CNTK V 2.0 Beta 12 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](https://github.com/Microsoft/CNTK/wiki/CNTK-Docker-Containers).

***2017-02-23.* V 2.0 Beta 12 Release**  
Highlights of this Release:
* New and updated features: new activation functions, support of `Argmax` and `Argmin`, improved performance of `numpy` interop, new functionality of existing operators, and more.
* [CNTK for CPU on Windows can now be installed via `pip install` on Anaconda 3](https://github.com/Microsoft/CNTK/wiki/Setup-CNTK-on-your-machine). Other configurations will be enabled soon.
* HTK deserializers are now exposed in Python. All deserializers are exposed in C++.
* The memory pool implementation of CNTK has been updated with a new global optimization algorithm. Hyper memory compression has been removed.
* New features in C++ API.
* [New Eval examples for RNN models](https://github.com/Microsoft/CNTK/blob/master/Examples/Evaluation/CNTKLibraryCSEvalCPUOnlyExamples/CNTKLibraryCSEvalExamples.cs).
* New [CNTK NuGet Packages](https://github.com/Microsoft/CNTK/wiki/NuGet-Package) with CNTK V2 C++ Library.

See more in the [Release Notes](https://github.com/Microsoft/CNTK/wiki/CNTK_2_0_beta_12_Release_Notes).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

***2017-02-13.* V 2.0 Beta 11 Release available at Docker Hub**  
CNTK V 2.0 Beta 11 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](https://github.com/Microsoft/CNTK/wiki/CNTK-Docker-Containers).

See [all news](https://github.com/Microsoft/CNTK/wiki/News).