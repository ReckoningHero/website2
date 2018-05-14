---
layout: post
title: The 5 best programming languages for AI development

---
The 5 best programming languages for AI development

1. Python
At number one, it’s Python. How could it be anything else, really? While there are maddening things about Python—the whitespacing, the massive split between Python 2.x and Python 3.x, the five different packaging systems that are all broken in different ways—if you’re doing AI work, you almost certainly will be using Python at some point.

The libraries available in Python are pretty much unparalleled in other languages. NumPy has become so ubiquitous it is almost a standard API for tensor operations, and Pandas brings R’s powerful and flexible dataframes to Python. For natural language processing (NLP), you have the venerable NLTK and the blazingly-fast SpaCy. For machine learning, there is the battle-tested Scikit-learn. And when it comes to deep learning, all of the current libraries (TensorFlow, PyTorch, Chainer, Apache MXNet, Theano, etc.) are effectively Python-first projects.

If you’re reading cutting-edge deep learning research on arXiv, then almost certainly you will find source code in Python. Then there are the other parts of the Python ecosystem. While IPython has become Jupyter Notebook, and less Python-centric, you will still find that most Jupyter Notebook users, and most of the notebooks shared online, use Python.

There’s no getting around it. Python is the language at the forefront of AI research, the one you’ll find the most machine learning and deep learning frameworks for, and the one that almost everybody in the AI world speaks. For these reasons, Python is first among AI programming languages, despite the fact that your author curses the whitespace issues at least once a day.

[ Learn Java from beginning concepts to advanced design patterns in this comprehensive 12-part course! ]
2. Java and friends
The JVM family of languages (Java, Scala, Kotlin, Clojure, etc.) is also a great choice for AI application development. You have a wealth of libraries available for all parts of the pipeline, whether it’s natural language processing (CoreNLP), tensor operations (ND4J), or a full GPU-accelerated deep learning stack (DL4J). Plus you get easy access to big data platforms like Apache Spark and Apache Hadoop.

Java is the lingua franca of most enterprises, and with the new language constructs available in Java 8 and Java 9, writing Java code is not the hateful experience many of us remember. Writing an AI application in Java may feel a touch boring, but it can get the job done—and you can use all your existing Java infrastructure for development, deployment, and monitoring.

3. C/C++
C/C++ is unlikely to be your first choice when developing an AI application, but if you’re working in an embedded environment, and you can’t afford the overhead of a Java Virtual Machine or a Python interpreter, C/C++ is the answer. When you need to wring every last bit of performance from the system, then you need to head back to the terrifying world of pointers.

Thankfully, modern C/C++ can be pleasant to write (honest!). You have a choice of approaches. You can either dive in at the bottom of the stack, using libraries like CUDA to write your own code that runs directly on your GPU, or you can use TensorFlow or Caffe to obtain access to flexible high-level APIs. The latter also allow you to import models that your data scientists may have built with Python and then run them in production with all the speed that C/C++ offers.

Keep an eye out for what Rust does in this space in the year to come. Combining the speed of C/C++ with type and data safety, Rust is a great choice for achieving production performance without creating security headaches. And a TensorFlow binding is available for it already.

4. JavaScript
JavaScript? What on earth is going on? Well, Google recently released TensorFlow.js, a WebGL-accelerated library that allows you to train and run machine learning models in your web browser. It also includes the Keras API and the ability to load and use models that were trained in regular TensorFlow. This is likely to draw a massive influx of developers into the AI space. While JavaScript doesn’t currently have the same access to machine learning libraries as the other languages listed here, soon developers will be adding neural networks to their webpages with almost the same nonchalance as they add a React component or a CSS property. Simultaneously empowering and terrifying.

TensorFlow.js is still in its early days. At the moment it works in the browser but not in Node.js. It also doesn’t yet implement the full TensorFlow API. However, I expect both of those issues will be mostly resolved by the end of 2018 and the JavaScript invasion of AI will follow shortly thereafter.

5. R
R comes in at the bottom of our top five, and is trending downward. R is the language that data scientists love. However, other programmers find R a little confusing when they first encounter it, due to its dataframe-centric approach. If you have a dedicated group of R developers, then it can make sense to use the integrations with TensorFlow, Keras, or H2O for research, prototyping, and experimentation, but I hesitate to recommend R for production usage, due to performance and operational concerns. While you can write performant R code that can be deployed on production servers, it will almost certainly be easier to take that R prototype and recode it in Java or Python.

Source: https://www.infoworld.com/article/3186599/artificial-intelligence/the-5-best-programming-languages-for-ai-development.html
