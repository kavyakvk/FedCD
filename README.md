# CS242-FedCD
A repo with code for the final project of Harvard's CS242 (Computing at Scale) on a new Federated Learning scheme, Federated Clone-Delete.

Oftentimes devices fit in the mold of one of many archetypes, where an archetype describes a specific group of non-iid data. Previously proposed learning schemes compromise on a model fine-tuned to perform well on a specific archetype in favor of a single model that works well for all archetypes, accept significant communication costs, or break the FL assumptions through a globally shared dataset. 

We propose Federated Cloning and Deletion, or FedCD, a learning scheme that results in tailored models for each archetype while allowing federated learning from other edge devices through iterative cloning of models at specified milestones, adaptive updating of a highly-ranked subset of global models, and deletion of poor-performance models. We argue that by using the proposed efficient learning scheme, we can decrease the size of the model to be trained and the number of times edge devices communicate with the central learner.
