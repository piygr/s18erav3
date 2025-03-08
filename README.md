# AI Assistant - S18ERAv3
### Phi 2 Model (with 2 Billion parameters) fine-tuned using [OpenAssistant/oasst1 dataset](https://huggingface.co/datasets/OpenAssistant/oasst1)

[Link to huggingface space App](https://huggingface.co/spaces/piyushgrover/ChatAssistant-S18ERAv3)

[Link to Phi2 QLoRA Adapter Weights](https://huggingface.co/piyushgrover/phi2-qlora-adapter-s18erav3)

### Training Logs
```
Step	Training Loss
10	11.645900
20	12.338500
30	13.316600
40	11.051500
50	13.083700
60	12.553500
70	10.825500
80	13.694400
90	11.034800
100	11.296900
110	14.271200
120	10.675800
130	11.726500
140	12.573100
150	10.642000
160	13.521600
170	10.754300
180	10.840700
190	13.381500
200	10.501300
210	11.764300
220	12.672600
230	10.703900
240	12.568900
250	10.906300
260	10.095100
270	12.698400
280	10.411600
290	11.194900
300	11.912900
310	10.226900
320	12.264100
330	12.110400
340	9.862900
350	12.034300
360	10.009800
370	10.557400
380	11.746800
390	9.722100
400	11.161100
410	11.354700
420	9.794900
430	12.005000
440	10.141300
450	10.041100
460	11.348400
470	9.566500
480	10.576000
490	10.504600
500	9.536300
TrainOutput(global_step=500, training_loss=11.38444842529297, metrics={'train_runtime': 7163.9105, 'train_samples_per_second': 2.233, 'train_steps_per_second': 0.07, 'total_flos': 5.233902520516608e+16, 'train_loss': 11.38444842529297})
```

## Sample Outputs
```
prompt = "\n\n### User:\nWhat was the role of indian revolutionaries in indian independence movement ?\n\n### Assistant:\n"
Output:
### User:
What was the role of indian revolutionaries in indian independence movement ?

### Assistant:
Indian revolutionaries played a significant role in the Indian independence movement. They were individuals who used various means, including violence, to fight against British colonial rule and to promote the idea of an independent India.

The Indian revolutionaries were inspired by the ideas of nationalism and freedom that were spreading throughout the world at the time. They were influenced by the writings of Indian leaders such as Mahatma Gandhi, Jawaharlal Nehru, and Subhash Chandra Bose, who advocated for non-violent resistance and armed struggle against British rule.

The revolutionaries used various methods to carry out their activities, including assassinations of British officials, bombings, and sabotage. Some of the most famous Indian revolutionaries include Bhagat Singh, Sukhdev Thapar, and Rash Behari Bose.

The revolutionaries were also involved in the formation of various organizations, such as the Hindustan Socialist Republican Association (HSRA) and the Ghadar Party, which aimed to promote the idea of an independent India and to carry out armed struggle against British rule.

The role of Indian revolutionaries in the Indian independence movement was significant, as they helped to raise awareness about the need for independence and to mobilize people against British rule. Their actions inspired many others to join the fight for independence, and their legacy continues to be remembered today.

In conclusion, Indian revolutionaries played a crucial role in the Indian independence movement by using various means to fight against British colonial rule and to promote the idea of an independent India. Their actions continue to inspire people today, and their legacy is an important part of India's history.
```

```
prompt = '''### User:\nExplain CNN to a five year old.\n\n### Assistant:\nA Convolutional Neural Network (CNN) is like a special kind of computer brain that can look at pictures and understand what they are about. It's like a big puzzle solver that can find patterns and shapes in pictures.\nImagine you have a picture of a cat. A CNN can look at each tiny piece of the picture, called a pixel, and figure out what color it is. Then it can look at the colors of the pixels around it and figure out if they make up the cat's fur or its eyes. It can do this over and over again, looking at different parts of the picture, until it understands the whole picture and knows it's a cat.\nCNNs are used in lots of different things, like helping robots see and understand the world around them, or helping doctors look at X-rays and find problems in our bodies. They're really smart and can do lots of things that humans can do, but even better!\nSo, in short, a CNN is a special kind of computer brain that can look at pictures and understand what they are about by finding patterns and shapes in them. It's like a big puzzle solver that can do things that humans can do, but even better!\nI hope that helps you understand what a CNN is! Let me know if you have any other questions.\n\n### User:\nWhat does it mean by convolution here?\n\n### Assistant:\n'''
Output:
### User:
Explain CNN to a five year old.

### Assistant:
A Convolutional Neural Network (CNN) is like a special kind of computer brain that can look at pictures and understand what they are about. It's like a big puzzle solver that can find patterns and shapes in pictures.
Imagine you have a picture of a cat. A CNN can look at each tiny piece of the picture, called a pixel, and figure out what color it is. Then it can look at the colors of the pixels around it and figure out if they make up the cat's fur or its eyes. It can do this over and over again, looking at different parts of the picture, until it understands the whole picture and knows it's a cat.
CNNs are used in lots of different things, like helping robots see and understand the world around them, or helping doctors look at X-rays and find problems in our bodies. They're really smart and can do lots of things that humans can do, but even better!
So, in short, a CNN is a special kind of computer brain that can look at pictures and understand what they are about by finding patterns and shapes in them. It's like a big puzzle solver that can do things that humans can do, but even better!
I hope that helps you understand what a CNN is! Let me know if you have any other questions.

### User:
What does it mean by convolution here?

### Assistant:
Convolution is a special kind of math that a CNN uses to look at pictures. It's like a way of sliding a small piece of the picture, called a filter, over the whole picture and looking at how the colors in the filter match up with the colors in the picture.
The filter is like a little puzzle piece that the CNN uses to find patterns and shapes in the picture. It's made up of lots of tiny dots, each with a different color. When the CNN slides the filter over the picture, it looks at how the colors in the filter match up with the colors in the picture. If the colors in the filter match up well with the colors in the picture, it means that the filter is looking at a part of the picture that is similar to the part of the picture that the filter is covering.
The CNN does this over and over again, sliding the filter over different parts of the picture, until it
```
