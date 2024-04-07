# Legal Document Generator

This project is a Python script that uses the LangChain library and the OpenAI language model to generate legal documents based on user input. The script prompts the user for information about the document, such as the sending party, document type, receiving party, relationship between the parties, and additional details. It then generates a legally binding document using the provided information.
Features

    Generates legal documents, such as license agreements, non-disclosure agreements, wills, and rental agreements, based on user input.
    Uses the OpenAI language model to ensure the document is written in clear, concise, and legally binding language.
    Saves the generated document as a Microsoft Word (.docx) file.
# Requirements

    Python 3.x
    OpenAI API key
    LangChain library


# Few-Shot Prompting

The script uses the LangChain library's FewShotPromptTemplate to generate the legal documents. This technique involves providing the language model with a few examples of the desired output, which helps it understand the structure and content of the document. The examples are stored in the examples list in the script and are used to create the prompt for the language model.
