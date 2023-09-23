In code,we installed langchain and openAi library.
OpenAi key is stored in some environment variable that can be used.
We have a directory loader which is a utility used to read directory that contains files.
And unstructured loader is a loader class present in directory loader,which is going to load various types of files such as text and pdf files.
After running the data directory,we get the number of documents present in that particular directory.
Then we splitted these documents to create chunks by using LangChain.
So TextSplitter takes our document and gives us chunks to create the OpenAi Embeddings.
