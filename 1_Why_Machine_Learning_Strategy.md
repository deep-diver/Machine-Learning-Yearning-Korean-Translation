## 1 Why Machine Learning Strategy

머신러닝은 셀 수 없을 정도로 많은 중요한 어플리케이션의 근간을 이룬다. 이는 웹 검색, 이메일 스팸처리, 음성 인식, 상품 추천과 같은 것을 포함한다. 당신 또는 당신이 속한 팀이 머신러닝 어플리케이션 제작 중에 있다면, 당신은 아마도 빠른 진척을 만들어 내기를 원할 것이다. 이 책은 당신이 그렇게 할 수 있게 도와줄 것이다.

#### Example: Building a cat picture startup
당신이 스타트업을 만들었고, 고양이를 사랑하는 사람들에게 끊임 없는 고양이 사진을 제공하려고 한다고 가정해 보자.

<img src="./1_Cat.PNG" style="text-align:center;" />

You use a neural network to build a computer vision system for detecting cats in pictures.
But tragically, your learning algorithm’s accuracy is not yet good enough. You are under
tremendous pressure to improve your cat detector. What do you do?
Your team has a lot of ideas, such as:
- Get more data: Collect more pictures of cats.
- Collect a more diverse training set. For example, pictures of cats in unusual positions; cats
with unusual coloration; pictures shot with a variety of camera settings; ….
- Train the algorithm longer, by running more gradient descent iterations.
- Try a bigger neural network, with more layers/hidden units/parameters.
- Try a smaller neural network.
- Try adding regularization (such as L2 regularization).
- Change the neural network architecture (activation function, number of hidden units, etc.)
- …

If you choose well among these possible directions, you’ll build the leading cat picture
platform, and lead your company to success. If you choose poorly, you might waste months.
How do you proceed?
This book will tell you how. Most machine learning problems leave clues that tell you what’s
useful to try, and what’s not useful to try. Learning to read those clues will save you months
or years of development time.
