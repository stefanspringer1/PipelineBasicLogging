# PipelineBasicLogging

---

⚠️ **NOTE:**

This repository is _deprecated;_ use the following, currently maintained repository instead:

https://github.com/swiftxml/PipelineBasicLogging

**Note the reset version number:** The last version of this repository corresponds to version 1.0.0 of the new repository.

---

This implements the use of [BasicLogging](https://github.com/stefanspringer1/BasicLogging) for the [Pipeline](https://github.com/stefanspringer1/Pipeline) library.

The Pipeline library allows the use of other logging libraries, so you can alternatively use a logging library of your choice (you might then at least use the [PipelineLoggingBinding](https://github.com/stefanspringer1/PipelineLoggingBinding) library). However, if no such logging library is specified or available, or if you simply want to try out the Pipeline library, this package provides a quick starting point.

Note that the Pipeline library's logging concept requires that a binding to a logging library must first be created, and then the logging in the application code can be formulated independently of the actual logging library. This means the logging library can easily be changed later without having to replace the logging commands.

This logging library already includes such a binding to the Pipeline library.
