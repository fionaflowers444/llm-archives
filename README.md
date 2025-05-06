# llm-archives

### Instructions

Click the "Use this template" button for this repository and choose "Create a new repository". You can give it the same name (llm-archives).

Once it's ready, go to [Groq](https://console.groq.com/keys) and follow the directions to get an API key. You'll need to login (or create an account if you don't have one).

Copy the API key value and then click on the Settings of your GitHub repository and click on "Secrets and variables" on the left side, then choose "Codespaces"

Click the green "New Repository Secret" button and paste your API Key into the "Secret" box, then put GROQ_API_KEY in the Name box above it. Click "Add Secret" and click on the name of the repository to return to the main page.

From there, click the green "Code" button and create a new Codespace in the Codespaces tab.

In the Terminal type the following: pip install requests groq and hit enter.

Then type: python get_stories.py

You should see a file called cns_maryland_posts.json appear. Let's look at it. It contains some details of the past 10 CNS stories.

Back in the Terminal, type: python entity_extraction.py and watch the output.

### Evaluation for JOUR389W

PUT YOUR EVALUATION HERE

This excercise was actually pretty impressive. The LM was able to classify all the people, places and organizations discussed in my initial input, a recent NYT article. The article explored President Trump's disengagement from the conflict between Israel and Palestine ahead of his visit to the Middle East, so there were a lot of organization names and prominent global figures refrenced throughout the piece. The LM performed well; all the main players were identified properly and none disregarded.
This archive could be incredibly useful for news organizations to employ, especially those as vast and efficient as the New York Times. Based on a Google search, the NYT releases around 150 pieces of journalism per day. A collection of entities like this could help better organize and classify what genre of publication each piece corresponds to, and could even be incorporated into the audience engagement aspect of the work. If users had an archive that listed people, places and dates that they could explore that would direct them to an assortment of articles on the subject they are aiming to explore, it could drive up viewership and make indivuduals more inclined to engage with the Times. The data assembled by the LM could be incredibly lucrative for organizational purposes. 
Users could input a specific name and be provided an extensive and complete list of articles that individual was mentioned in, which would make research much easier. The same goes for the name of an organization or place. From a legal perspective this could do wonders; for example, for some of my investigative work I am tasked with looking into controversies surrounding group and transitional housing. When I input these names into Google, most of what comes up is just the place's marketing; I have to dig deeper to find any substantial information they haven't tried to digitally sweep under the rug. For places that do have a controversial history, I will find it written about in some sort of publication, but the process to get there is tedious. If there was a system like this set up, I could simply input the name into the LM and be provided an archive of all the mentions of that specific place in articles, where the most relevant information is likely to be found. When I am doing plain internet searches, sometimes articles will not show up even when my specific input is mentioned by name in the bulk of the article since it does not appear in the headline. 
This tool could be very useful for investigative journalists and anyone looking to perform extensive research, as well as just anyone who has a centralized interest in a specific topic and wants to explore more deeply. The media surrounding the conflict in the Middle East is another example of its potential employment. There is such a surplus of journalism covering the tumultuous state of affairs, which could be overwhelming. If someone was looking to rad up on one specific aspect of the conflict they could input that to classify and organize the information in a more productive manner. 
I want to make an effort to familiarize myself with this aspect of technology within journalism. Coding and anything computer-science related scares me, but I can really see how this practice would be effectively implemented within the industry and want to get ahead of it now while it is still developing rather than rushing to catch up later on down the line. AI in journalism is here to stay, so instead of resisting it entirely this class has taught me how to better adapt and implement useful and efficient practices to improve the quality of my own work. 