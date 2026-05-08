Ideas: 1. meta llm gets propmt and decides which llm is suited best for it and forwards the prompt. Decision can be based on several factors e.g. cost, quality.
      2. meta llm gets prompt and generates several prompts out of that parent prompt and delegates the different child prompts to the best suited llms and builds 1 request answer from those outputs.
      3. meta llm checks the respond from the child llm and if necesarry adds contraints/rules to the prompt and delegates it again.
      4. meta llm sends the same prompt to several child llms and compares the responds. If they don't allign it is to be defiend what the meta llm does. In any case it generates 1 meta respons.

Evaluation: 1. N amount of test prompts specifically suited for 1 child llm are sent to the meta llm. Then it is imperically checked how often the orrect llm was chosen. 
            2. After the meta llm generated prompts from the original. Those prompts are evaluated as a whole to check that no information was lost.
            3. Quality of the first meta respons is compared to the quality if the meta respons after the prompt was adjusted by the meat llm.
            4. TBD.
