# JDK和 JRE的区别

## **1. JDK（Java Development Kit）**

## **定义**

JDK 是 **Java 开发工具包**，它是为开发者设计的完整工具集。JDK 包含 JRE（运行环境），并额外提供了开发 Java 程序所需的工具，如编译器和调试器。

## **组成**

- **JRE**：JDK 包含完整的 JRE，因此可以运行 Java 程序。
- **开发工具**：
  - **javac**：Java 编译器，将 .java 源代码编译成 .class 字节码。
  - **java**：运行 Java 程序的命令。
  - **javadoc**：生成 API 文档的工具。
  - **jar**：打包工具，用于创建 .jar 文件。
  - **调试和监控工具**：如 jdb（调试器）、jconsole（监控工具）等。
- **附加类库**：包括开发相关的库（如工具类、Swing 等）。

## **作用**

- JDK 是给 **开发者** 使用的，安装 JDK 后可以编写、编译和运行 Java 代码。
- 它是 Java 开发的完整环境。

## **使用场景**

- Java 程序员需要开发应用程序（例如写 Spring Boot 项目），必须安装 JDK。

## **2. JRE（Java Runtime Environment）**

- **定义**

JRE 是 **Java 运行时环境**，它是运行 Java 程序所必需的软件集合。JRE 提供了 Java 虚拟机（JVM）、核心类库（Java Class Library）以及其他运行 Java 程序所需的组件。

- **组成**

- **JVM（Java Virtual Machine）**：Java 虚拟机，负责解释和执行 Java 字节码（.class 文件），实现跨平台特性。
- **核心类库**：包括 Java 的标准库（如 java.lang、java.util 等），提供常用功能。
- **运行时支持文件**：如配置文件和本地库。

- **作用**

- JRE 是给 **用户** 或 **终端设备** 使用的，安装 JRE 后可以运行已经编译好的 Java 程序（.jar 文件或 .class 文件）。
- 它不包含开发工具，因此无法用来编写或编译 Java 代码。

- **使用场景**

- 如果你只是想运行 Java 应用程序（例如玩 Minecraft 或使用某些 Java 软件），只需要安装 JRE。

### 3.**JDK 和 JRE 的关系**

- **包含关系**：JDK 包含 JRE，JRE 是 JDK 的子集。
- **功能差异**：
  - JRE：只能运行 Java 程序。
  - JDK：可以开发和运行 Java 程序。
- **比喻**：
  - JRE 像是一个“播放器”，只能播放已经录好的视频。
  - JDK 像是一个“录制和播放一体机”，既能录制（开发）也能播放（运行）。
