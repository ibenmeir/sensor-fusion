# sensor-fusion
An inquiry into the problem of natural-language sensor fusion. 

As natural language processing takes on increasing importance in computing, the task of synthesizing the data collected by multiple sensors taking readings on the same phenomenon becomes problematic. It is easy to create a multi-sensor array using sensors that take numerical measurements – such as a chemical sensor array – but when the data collected is encoded in natural language, there is no ready metric available for synthesizing multiple inputs without an attendant loss of meaning. 

My intuition is that the solution to this problem is embedded in the problem, itself: the very same vector databases that enable large language models to interact with users in natural language can be understood as providing the framework needed to compare/synthesize natural-language data points with a minimal loss of meaning, insofar as they operate by projecting natural language into a complex system of mathematical representations thereof. 

This intuition, however, does not reach the question of mechanism; hence, further research is required. Can an LLM "do the math" required for natural language sensor fusion – and if so, what kind of prompting is required? Can an LLM's "embeddings" be abstracted from the model itself, and used as the basis for a natural language sensor fusion process that does not otherwise involve the "source" LLM? Since some measure of meaning must be lost in the process of making natural language computable, is it possible to identify where and how these losses are likeliest to take place, and to develop ways of mitigating them? 

This work has important implications, specifically in the area of public opinion research, which has become less and less reliable as older ways of "taking the temperature of the public" have struggled to consistently provide accurate readings. Good governance requires good data, and good data depends on functional sensors. In some ways, the problem of natural language sensor fusion is the problem of democracy itself: How can disparate perspectives be synthesized into a clear signal, while respecting the messiness of the discourse from which that signal emerges?  


I am a PhD candidate in English at Brown University, where I'm finishing a dissertation on the impact of LLMs on language, literature, and literary studies, and a researcher and editor at BlockScience, where much of my work also involves thinking through the ways that artificial intelligence will impact the sociotechnical systems that increasingly define our world.  
