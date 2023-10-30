用例图是Unified Modeling Language (UML) 中的一种结构图，用于描述系统与其外部实体（通常是用户或其他系统）之间的功能性需求和交互。
用例图通常包括用例（表示系统的功能或操作）、参与者（表示与系统交互的外部实体）、以及它们之间的关系

1.包含关系（<<   includes  >>）：表示一个用例包含另一个用例，这意味着在执行包含用例时，还会执行被包含用例的部分。
2.扩展关系（<<   extends   >>）：表示一个用例可以在另一个用例之上进行扩展，这意味着在某些条件下，扩展用例可以在被扩展用例的基础上执行。
3.使用关系（<<     uses    >>）：表示系统使用一个用例来完成某些功能。

椭圆形 ：用例表示系统的不同功能或操作，通常与系统的用户或外部实体有关。每个用例代表系统的一个具体功能或操作。用例通常用椭圆形表示，名称位于椭圆内部。
参与者　：参与者表示与系统交互的外部实体，可以是用户、另一个系统或设备等。参与者通常用小人图标或简单的方框表示，它们位于用例图的左侧或顶部。
系统边界：系统边界是一个方框，用来表示系统的范围和边界，将系统内部元素和外部参与者区分开来。
注释　　：注释可以附加在用例图上，用于提供额外的解释、说明或注解。通常用虚线带箭头的线连接到相关元素，并包含文字描述。
