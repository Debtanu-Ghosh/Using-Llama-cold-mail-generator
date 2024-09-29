# Cold-mail-generator

A software services company has built a tool using Groq, Langchain, and Streamlit. The tool lets users enter a company's career page URL. It then pulls job listings from the page and creates custom cold emails. These emails include links to portfolios, which are picked from a vector database based on the job descriptions.

**For example:**

Ram is looking for a Principal Software Engineer. They are spending a lot of time and money on hiring, onboarding, and training. ABC, a software development company, can provide Ram with a skilled engineer right away. Mohan, a business development executive from ABC, will send Ram a cold email offering their services.

![img2](./images/img2.png)

# Architecture Diagram

![img2](./images/img1.png)

# Set-up

- To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.

- To get started, first install the dependencies using:

           pip install -r requirements.txt

- Run the streamlit app:

          streamlit run app/main.py
