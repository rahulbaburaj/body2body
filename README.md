# body2body
Deep learning network to transfer body movements from one individual to another. Eg mimic dance steps. 
First of all, the project has not produced very promising results, all I intend to do is to give you a direction to think. I method used here can be adopted in many situations
For the motivation, let me walk you through some of the priliminary results. 

<a href="https://imgflip.com/gif/223qo6"><img src="https://i.imgflip.com/223qo6.gif" title="made at imgflip.com"/></a> . I agree the reconstruction is poor, but keep in mind the gan was trained on a 30 second superman animation. The superman video clearly didn't capture most of the required moviements and hence, the above result was expected.

Going into technical details of the project, I'll start with the basic idea. You just cant train a deep learning network from a given man to superman, because then the solution will be specific to that particular man. So you need something that is same for all people to stand as an intermediate layer. What I used is the pose estimation technique as given in the paper Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields.
https://drive.google.com/file/d/1ToKKeYhNdmI2M9w1Vp31WWRqnp2NfWU9/view?usp=sharing https://drive.google.com/file/d/1FPhaHviLbVdVN4iO6pMhiKtpEb-jVEql/view?usp=sharing



