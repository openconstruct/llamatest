# llamatest
To run you MUST have llama-server from the llamacpp project.
example

    ./llama-server -m model.gguf
    
or

    llama-server.exe -m model.gguf
    

 Once it's running, open the llamahtml file in a web browser, any modern browser should work.
  Type in a topic, or paste your info in the box
  select a number of questions and hit generate, it's pretty slow even on a model I get 20 tps on.
   Whether or not it parses correctly is model-dependent, I tested gemma 4, and deepseek coder v2 lite, both parsed correctly.
