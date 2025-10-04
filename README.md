# Jaideep_Singh_2210110675_MAT496

Module1:

Video1:
From the video, I understood that LangSmith provides observability into AI applications through a feature called tracing. It creates a detailed log, or a run tree, of every step your application takes, from the initial input to the final output. This makes it simple to debug issues and analyze performance by looking at metrics like latency for each step in the process.

Tweaking:
Imported and Added tracing to every function and asked llm about other methods of tracing, what type of metadata can I add?, an example of adding metadat during runtime
file: Jaideep_Singh_2210110675_MAT496/notebooks/module_1/tracing_basics.ipynb

Video2:
From the video, I understood that LangSmith uses different run types to categorize the steps in an application's trace, which helps in debugging. By assigning a specific run type, like LLM, retriever, or tool, each step gets a unique icon and format in the user interface. This makes the trace easier to read and allows you to filter for specific types of operations to analyze your application's behavior.

Tweaking:
Added a personalized greeting using the user's name in the tool response and input. Jaideep_Singh_2210110675_MAT496/notebooks/module_1/types_of_runs.ipynb cell 10

Video3:
LangSmith offers several tracing methods beyond the automatic traceable decorator and Langgraph. For more specific logging, you can use the trace() function or wrap_openai, while the RunTree class provides the most fine-grained control at the lowest level. This variety lets you choose the right balance between ease of use and detailed control for your application's needs.

Tweaking:
I tweaked Cell 11 by adding a function that prints a message when the LangGraph graph is compiled, providing user feedback.
file:Jaideep_Singh_2210110675_MAT496/notebooks/module_1/alternative_tracing_methods.ipynb
