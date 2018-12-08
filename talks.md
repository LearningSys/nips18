# Invited Talks

## Keynote 1: Accelerated Computing for AI, Bryan Catanzaro {#key1}

Training and deploying deep neural networks is computationally intensive, which has led to significant interest in accelerators for AI, including GPUs, TPUs, and various custom processors with a range of goals and capabilities. Although the need for accelerated computing seems clear, perhaps less appreciated is the need for programmability to accompany acceleration, and the entire systems stack that needs to work together to avoid Amdahl's law bottlenecks. In this talk, I will discuss how we approach creating software and hardware to help researchers invent, train and deploy the models of the future, illustrating with details about Volta and Turing GPUs, NVSwitch based system interconnect, CUDNN, and TensorRT.

Bryan Catanzaro is VP of Applied Deep Learning Research at NVIDIA, where he leads a team solving problems in domains ranging from video games to chip design using deep learning. Bryan earned his PhD from Berkeley, where he focused on parallel computing, machine learning, and programming models. Bryan worked at Baidu to create next generation systems for training and deploying deep learning models for speech recognition. Before that, he was a researcher at NVIDIA, where he worked on programming models for parallel processors, as well as libraries for deep learning, which culminated in the creation of the widely used CUDNN library.

[**Slides**](slides/Catanzaro_AI_Systems_Workshop_2018.pdf)


## Keynote 2: BREAKING NEWS: Types Found to Be Underrated, Aish Fenton {#key2}

In this talk Aish will make the case that types (as in generic programming types) are under appreciated in the ML community and are vital for working with industry scale machine learning. He'll walk through several practical examples of where types can mitigate commons bugs, and provide opportunities for deeper optimization of numerical code.

Aish is a Research Manager at Netflix. He leads the machine learning research team there for recommender systems and search algorithms. Aish has over 22 years of experience at the intersection of mathematics and software engineering. Prior to Netflix, Aish headed data science at Opentable, Foodspotting, iVistra, and founded the company, vWork, solving large-scale logistics optimization problems.


## Keynote 3: Infrastructure and Systems for Applied Machine Learning at Facebook, Kim Hazelwood {#key3}

Machine learning sits at the core of many essential products and services at Facebook. This presentation will describe the hardware and software infrastructure that supports machine learning at global scale. Facebook’s machine learning workloads are extremely diverse: services require many different types of models in practice. This diversity has implications at all layers in the system stack. In addition, the amount of data flowing through machine learning pipelines presents practical challenges in delivering data to high-performance distributed training flows. Computational requirements are also intense, leveraging abundant general-purpose and more limited specialized computing platforms for training and real-time inference. Addressing these and other emerging challenges continues to require diverse efforts that span machine learning algorithms, software, and hardware design.

Kim Hazelwood is a Senior Engineering Manager leading the AI Infrastructure Foundation efforts at Facebook, which focus on the hardware and software platform design and efficiency for Facebook's many applied machine learning-based products and services. Prior to Facebook, Kim held positions including tenured Associate Professor at the University of Virginia, Software Engineer at Google, and Director of Systems Research at Yahoo Labs. She received a PhD in Computer Science from Harvard University in 2004, and is the recipient of an NSF CAREER Award, the Anita Borg Early Career Award, the MIT Technology Review Top 35 Innovators under 35 Award, and the ACM SIGPLAN 10-Year Test of Time Award. She currently serves on the Board of Directors of CRA, and has authored over 50 conference papers and one book.
