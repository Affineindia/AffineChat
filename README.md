# AffineChat
Introducing [Affine Chat](https://dolly-bot.streamlit.app/) – the innovative app designed to revolutionize the way you interact with your files. This app showcases the power of LLMs to create a unique file management experience. With AffineChat, you can effortlessly index and search through your PDFs, text files, and multimedia files, empowering you to have meaningful interactions with them.


So how does AffineChat work? Quite simple. The backbone of AffineChat are these components: 
1.	PyPDF to convert PDF files into simple text.
2.	OpenAI Whisper for transcribing your audio and video files into text.
3.	Langchain for indexing the textual information.
4.	Sentence Transformer ‘all-mpnet-base-v2’ embeddings for filtering information.
5.	Databricks Dolly LLM for language processing
6.	Streamlit for the straightforward UI


AffineChat takes file management to the next level by transforming your documents into interactive knowledge hubs. Simply ask a question, and the app's intelligent algorithms will swiftly filter through your file, pinpointing the exact answers you need. No need to dig through endlessly through your files – AffineChat brings the information you seek right away.


But that's not all! AffineChat goes beyond just providing answers. It also showcases the source of information, allowing you to trace back in case you want to get a bit deeper. Whether you're a researcher, a student, a professional, or simply someone with a vast digital library, AffineChat enables you to have meaningful conversations with your files, unlocking their full potential and transforming the way you interact with your knowledge.


Thanks to the seamless integration of Databricks and AWS cluster, we achieved a quick deployment of the app, saving significant time and effort in setup and management. Leveraging the GPU capabilities of AWS helped us further enhance the app's performance. To provide an intuitive user experience, we chose Streamlit as the framework to power AffineChat, ensuring a simple and intuitive interface. This combination of technologies and platforms enabled us to deliver an efficient and enjoyable user experience with ease. 


AffineChat is an exciting demonstration of what's possible when cutting-edge open-source technologies are combined. It’s just a starting point. It showcases the potential to streamline file management, enhance productivity, and unlock the full potential of your files. So, take a leap and experiece the future of file management with AffineChat. For us, it’s only matter of time even the operating systems would come integrated with AI-assisted file management. And our effort is nothing but a small step in that direction.
