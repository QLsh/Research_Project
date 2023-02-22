# Research_Project
This is a repository with all the material for my Master's project.


## Exploring the Invisible Land in an Apple

I still remember the first time I read the book called The Map of the Invisible. The author asked a question at the beginning of the book: imagine you have an apple, you cut it in half, then cut it in half again, and again, and keep doing that. What will you end up with? I guess it is pretty normal to have such a stage in life, being curious about the most basic but eccentric questions. As time passed, most people forgot about these 'stupid' thoughts and started to focus on more 'important' things in life. Fortunately, you are not one of them. You are still wondering whether there is an answer to that question. Congratulations, this is the first step before entering the gate of particle physics.

Let's go back to the question about the apple. After billions of cutting, we end up with a set of minor constituents called atoms. If the same logic can be applied to this element, what will be inside it? Will there be anything inside? The answer is yes. The model of atoms was discovered and finalized a century ago by Thompson, Rutherford and Schr\" {o}dinger. Atoms were proved to consist of sub-atomic particles. However, this is still not the end of this path. 

"...Discoveries in this field since the 1930s have resulted in a remarkable insight into the fundamental structure of matter: Everything in the universe is found to be made from a few basic building blocks called fundamental particles. Our best understanding of how these particles are encapsulated in the Standard Model(SM) of particle physics." Quoted from the website of CERN introducing the establishment of SM. 

Nevertheless, by then, there was one last missing puzzle in SM: the Higgs boson. It was predicted in the 1960s and finally discovered in 2012 at CERN's Large Hadron Collider. Analysing the properties of this particle became one of the principal interests in this field. This project is also designed for the same purpose.

This goal can be achieved by reconstructions of observables. The decay products of the Higgs boson can be an excellent point to start with for the reconstructions. The obstacle in this process is to predict the kinematics of neutrinos, as it is the so-called invisible particle and is not detectable. This project uses ML techniques, especially Deep Neural Networks, to predict neutrinos without building any explicit physics model. This model used Monte Carlo truth as the learning target. This way, further analysis of the observables can be carried out based on the prediction. 

Apart from fundamental observables such as mass, spin and parity, the CP state is another essential property to explore. An angle between two decaying planes of Higgs decaying products is defined as acoplanarity angle. It was cumbersome to evaluate data for too many distinct acoplanarity angle sensitivities. ML techniques can then be implemented again to simplify the process. This study improved the previous separation of this angle for one of the decay channel by approximately 26\%.

We can see that the improvement of equipment and technical tools sizably accelerated the development of science in the history of particle physics. From the discovery of the Higgs boson to the breakthrough in its further analysis, each step is significant and cheerful. No matter how little knowledge we have at each stage, extracting as much information as possible from the limited condition. We grabbed all the chances like beasts. This will always be the spirit on the way to this endless road. 

Hope the thoughts of wondering about the result of cutting apples never fade in your mind.




Machine learning(ML) techniques are finding increasing applications in high-energy physics data analysis. Extracting as much information as possible from low-level variables and implementing ML techniques with this information has become a principal interest in this field. This allows an algorithm to learn the results without explicit physics models. This paper discusses how much improvement can be introduced by ML techniques, especially by implementing DNN, to the measurement of CP-sensitive observable $\phi_{CP}$ of the Higgs boson. By implementing a multi-output DNN regressor to predict the momentum of neutrinos decayed from $\tau$ leptons, the discrimination between the CP-even(scalar) and CP-odd(pseudo-scalar) improved vastly when both $\tau$ leptons undergo $\pi$ decays. More improvements can be expected for other decay modes once the reconstruction of $\phi_{CP}$ is correct.

Machine learning(ML) techniques have been rapidly finding a place in high-energy physics data analysis such as data selection, data classification and further predictions. Various applications of ML techniques allow improvements in reconstructing high-level physics quantities without specific physics models. It shows the probability of having a general model and improves the efficiency of data analysis. This study addressed the application of ML techniques, especially Deep Neural Network(DNN), in measuring the Higgs boson CP state. 


## Measurement of CP states

After the discovery of the Higgs boson by LHC experiments in 2012, a large and growing amount of literature has investigated other basic quantum numbers such as mass, spin and parity which is crucial for studying the feature of Higgs boson. Its CP state is one of the most significant properties of Higgs boson that help us achieve a better understanding of this particle. 

Extensive research has been conducted to measure the CP state of the Higgs boson. For example, the Standard Model predicts that the Higgs boson is purely CP even. Therefore, any CP odd measurements will imply physics beyond Standard Model and worth carrying analysis. 
 
As was stated in 1993 by Kramer, one way to achieve that can be accomplished by measuring the transverse spin correlations. One of the most powerful methods to do that is through its decay to $\tau$ leptons. This is based on the sensitivity of the transverse spin to the parity of the Higgs. This sensitivity can be indicated by angular correlations of secondary decay products, particularly in the distribution of the products from $\tau$ decays.
 
However, the main limitation of this method is the validity of detecting the loss of neutrinos and evaluating the detector precision. Therefore, based on Kramer's work, Bower improved the method of measuring the parity of the Higgs in 2002. Even though it does not need to adapt the measurements from LHC and the reconstruction of $\tau$ rest-frames, the method only applied to the dominant $\tau$ decay channels. This is because it is relatively easier to define the acoplanarity angle in this decay mode. In light of this study, extending to other decay modes has become particularly important for the next stage.
 
In addition, the secondary decay products $\pi^0$, $\pi^{\pm}$ and most importantly, the neutrinos. The neutrinos are the so-called Invisibles and cannot be detected directly from the collision. One crucial step before analyzing the Higgs boson's property is reconstructing the neutrinos with valuable features such as the directions and angular-related information, which will be mentioned later in the study.
 
In most of the following publications, a well-established idea is that the promising potential improvement in achieving sensitivity to Higgs CP states can be starting to use information in $\tau$ decay vertex. For example, Ralph Jozefowicz and his colleagues have concentrated only on the sensitivity to CP states during Higgs decaying through analyzing acoplanarity angles. Instead of exploring the effect of the decay vertex, they studied more essential details in the cascade $\tau$ decay. Based on Bower's work, they improved the definition of acoplanarity angle and split the events into more groups so that it can be used to discriminate more decay modes.
