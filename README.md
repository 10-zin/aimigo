# aimigo

## General Thought

your AI friend, so that you don't get bored.

Some multimodal GPT shit that can work on pc, or mobile.

Is funny no-filter just like X's Grokk, just like a true friend.

Is real-time connected to social media. Draws inspiration for new content. 

Speech-to-Speech: I talk, it talks.

Can see my screen: So that we have fun interesting convos about topics I am currently interested in.

Memory: keeps memory of all past convos, and retrieves fond memories in b/w just like a real friend.


## Technical's

Use edge-device QWEN type multimodal model. Possibly not feasible. Then - Host QWEN type model on private cloud cpu-vm (use free credits on new account).
Optimize for fast inference -> gotta think more on this.

Store memory in some no-sql like mongo/dynamodb 
RAG module to occasionaly fetch memories.

Make the LLM have GROK like cunning funny personality. - RLHF?? Instruction tuning?? Distill train on Grokk?? existing Open-Source GROKK??

Access to screen -> gotta figure this out. Some mac screen record input to LLMs in 1s frame chunks??

Video and Audio access ??? compress frames (resolution) , also compress audio (sample rate/ bit rate ???)

UI for a hovering siri like thing on my mac to control it. like I can hard pause the friend, when i wanna.
