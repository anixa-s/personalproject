**The project was completed with the following libraries:**
from langchain.document_loaders import DirectoryLoader
from langchain_community.document_loaders import PyPDFDirectoryLoader
from langchain.text_splitter import RecursiveCharacterTextSplitter
from langchain.schema import Document
from langchain_core.output_parsers import StrOutputParser
from langchain_community.llms import Ollama
from langchain.vectorstores import Chroma
from langchain_community.embeddings import HuggingFaceEmbeddings
from langchain.prompts import ChatPromptTemplate 
from dotenv import load_dotenv
import os
import shutil

**Install the following in your VS Code terminal:**
pip install langchain 
pip install chromadb  
pip install PyPDFLoader 