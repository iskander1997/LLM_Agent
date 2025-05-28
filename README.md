What is this?
A Python implementation of an intelligent agent that uses Mistral LLM to automatically select and execute the right tools based on natural language requests. Instead of calling functions directly, you just ask what you want in plain English.
How It Works
The agent acts as a middleware between you and your functions. When you say "What's the weather in Paris?" or "Calculate a times b plus 1", Mistral analyzes your request, picks the appropriate tool (weather API or calculator which is an implemented function), generates the Python code, and executes it safely.
Key Features
🤖 Intelligent Tool Selection: Mistral reads your request and automatically chooses between available tools (weather checker Or specific calculator "Skono_calculator" (a*b+1) )
🔧 Extensible: Easy to add new tools - just register them and the agent learns to use them automatically
🛡️ Safe Execution: Generated code runs in a controlled environment with proper error handling
