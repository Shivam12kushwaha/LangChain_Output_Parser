# LangChain Output Parser
#### Ouput Parser in LangChain help convert raw LLM response into structure formats like JSON,CSV,Pydantic models and more. They ensure consistency, validation and ease of use in applications.
## Types of Output Parser:
### (1) StrOutputParser
####    The StrOutputParser is the simplest output parser in LangChain. It is used to parse the output of a LLM and return it as a plain string.
### (2) JSONOutputParser
####    In LangChain, a JSONOutputParser is used when you want to ensure that the output from an LLM conforms strictly to a JSON structure data extraction, API-ready responses and interfacing with databases otr downstream application.
### (3) StructuredOutputparser
####    StructuredOutputParser is an output parser in LangChian that helps extract strucutred JSON data from LLM response based on predefined field schemes. It works by defining a list of fields (Response Schema) that the model shoould return, ensurin the output follows a structured format. But it has disadvantage Data Validation. To overcome this problem, we use PydanticOutputParser. 
### (4) PydanticOutputParser
####    Is is a structured Output parser in LangChain that uses Pydantic models to enforce schema validation when processing LLM responses.
