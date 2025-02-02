# LLmaaS
Local LLM as a Service

## Components
```
+----------------------------+
|        Web Browser         |
|  - Renders HTML            |
|  - Handles message history |
|  - Displays chat messages  |
+------------+---------------+
             |
             v
+----------------------------+
|    LLmaaS Proxy Server     |
|  - Enables browser access  |
|    to local LLM resource   |
+------------+---------------+
             |
             v
+----------------------------+
|     Local LLM Service      |
|  (e.g., Ollama, Llama.cpp) |
|  - Processes requests      |
|  - Generates responses     |
+----------------------------+
```



## Flask proxy

### Start flask proxy

The proxy takes 2 optional parameters
1 - local Ollama generate URL
2 - model name
(The default values are the same as seen in the example call) 
`python flask_llm_streaming_proxy.py http://localhost:11434/api/generate llama3.1`


## Demo page
[LLmaaS demo](https://devquasar.com/llmaas/)

[<img src="https://raw.githubusercontent.com/csabakecskemeti/devquasar/main/dq_logo_black-transparent.png" width="200"/>](https://devquasar.com)

'Make knowledge free for everyone'

<a href='https://ko-fi.com/L4L416YX7C' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi6.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
