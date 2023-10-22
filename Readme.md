# ObjPasUtils

This Package aims at providing a set of useful functions, and types for FreePascal.

It is based on and extends RecUtils (https://github.com/Warfley/Recutils) in order to provide a consistent package.

While for RecUtils all the units are independent, this provides all the units as one package, allowing the units to use each other and provide their full potential in combination.
Also unlike RecUtils, this repository provides more than just record types, but also classes and functions.

This is a collection of small interconnected libraries found in the `src` directory:
* DynamicTypes: Custom types for dynamically managing data of different types
* Iterators: Collection independent library for iterating over streams of data (e.g. the elements of an array) and modifying such streams (map, filter, reduce, etc.)
* Pathlib: Custom Path type containing path management, resolution and simple file management functions. Automatically handles Windows and Unix paths
* Range: Views on Subsets over types and data, e.g. only considering a subset of array data without having to copy the data into a new array
* Tuple: Implementation of tuples, Types that contain multiple fields of different types, up to 5 elements

Further explainations can be found in the Readme of the different directories in `src`. See the `examples` directory for examples on how to use the units provided by this package.




#  ObjPasUtils

本软件包旨在为 FreePascal 提供一组有用的函数和类型。

它基于并扩展了 RecUtils (https://github.com/Warfley/Recutils)，以提供一个一致的软件包。

在 RecUtils 中，所有单元都是独立的，而本软件包将所有单元作为一个软件包提供，允许各单元相互使用，并在组合中充分发挥其潜力。与 RecUtils 不同的是，该资源库提供的不仅仅是记录类型，还有类和函数。

这是在 src 目录中找到的相互关联的小型库的集合：

动态类型： 用于动态管理不同类型数据的自定义类型

迭代器： 独立于集合的库，用于迭代数据流（如数组的元素）和修改数据流（映射、过滤、还原等）。

路径库 自定义路径类型，包含路径管理、解析和简单文件管理功能。可自动处理 Windows 和 Unix 路径

范围 类型和数据子集视图，例如，只考虑数组数据的子集，而无需将数据复制到新数组中

元组 元组的实现，包含多个不同类型字段的类型，最多 5 个元素

更多解释请参见 src 不同目录的 Readme。有关如何使用本软件包提供的单元的示例，请参见示例目录。
