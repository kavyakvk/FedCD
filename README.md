# CS242-FedCD
Federated learning has been widely applied to enable decentralized devices, which each have their own local data, to learn a shared model. However, learning from real-world data can be challenging, as it is rarely identically and independently distributed (IID) across edge devices (a key assumption for current high-performing and low-bandwidth algorithms).  We present a novel approach, FedCD, which clones and deletes models to dynamically group devices with similar data. Experiments on the CIFAR-10 dataset show that FedCD achieves higher accuracy and faster convergence compared to a FedAvg baseline on non-IID data while incurring minimal computation, communication, and storage overheads. 

Final Project for Harvard CS 242: Computing at Scale

Paper Accepted and Oral Presentation at the AI of Things Workshop at the ACM International Conference on Knowledge Discovery and Data Mining (San Diego, CA), August 2020: https://aiotworkshop.github.io/accepted-papers.html

Additional Information: Paper on Arxiv https://arxiv.org/abs/2006.09637
