# Things
## PoC
### objectives
- Understand implications of having AsyncAPI and JSON schema documents as two equivalent mechanisms to specify data exchange between two parties

Things is a very simple semantic model in AIDM with core concept of Thing which can be dressed with an Instruction (to do something with the thing) and a Result (to report outcome of doing something with the Thing)

On this semantic model we have a message to instruct the other party to do something with the thing at hand. To keep things simple the message is limited to convey a single instruction at a time

In the PoC, party A sends an instruction, party B receives this instruction

### design
This interface is documented with a JSON schema (so, can only address payload of message) or as alternative with an AsyncAPI document (introducing channel, operation, and message notions on top of the payload schema)

AIDM I3, T3, T$ models for Things can be explored at https://pinggg.mywire.org/json/AIDM%20I3,%20T3,%20T4%20Things/index.htm  

AsyncAPI can be viewed in Studio at https://studio.asyncapi.com/?share=28528208-0be8-4fdd-a6cc-8cc064118a7b

JSON message schema can be viewed in Newton validator at https://www.jsonschemavalidator.net/s/qmC4CPnW


Individual artifacts can be downloaded from https://pinggg.mywire.org/json/ or Github https://github.com/eelcofolkertsma/Things