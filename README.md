A QA system built on your data and this solution stems from the question “What should you do if you want a pre-trained LLM to answer questions about unfamiliar topics like your non-public documents”

There are really two common ways to approach this problem. 

The first is Fine tuning, where we teach a 1) model how to answer a question, 2) that can entail the structure format, 3) the personality we’d like it to have and it goes hand in hand with properly forming prompts. And theres more to it but this is where we could start with fine-tuning a pre-trained llm.

The second is embedding which means providing the pre-trained model with new/specific information that i can use to answer questions and given that fits the mold of what we need to create our solution, we’re going to take that route. For example, our data will be whitepapers available on your public website
And the steps include:
1) throwing our whitepapers in a storage bucket
2) preparing our data. It all starts here, we can’t begin this journey without knowing where your data lives, how its stored, and preparing it so it can be used. In the case of this solution we’re going to use a vector database which is designed to handle unstructured data and how it does that is important but we can save that conversation for later
3) then we’re going to build out the logic on how to search through that data
4) and finally we can start asking it questions and receive answers.

   ![image](https://github.com/hasarahman/embeddings-whiteboard/assets/155875846/7be6fbb5-efaa-495d-9b5f-a349a5dd1877)

