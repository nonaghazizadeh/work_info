# Some notes about papers related to our works

The three papers that are named below with a short summary about their approach, are papers that helps us.

## ISPY: Automatic Issue-Solution Pair Extraction from Community Live Chats

In this paper they proposed an approach, named ISPY, to automatically extract issue-solution pairs from development community live chats. It use a basic CNN network with 15 heuristic attributes and Local-Attention mechanism to handle the characteristics of this task.
</br>
Image below is an example of ISPY:

<img width="454" alt="image" src="https://user-images.githubusercontent.com/59199865/212191268-fa76f354-7880-4079-8c8d-9029693ba047.png">

## Predicting the objective and priority of issue reports in software repositories

In this paper they proposed a two-stage approach to predict both objective and importance of issue reports posted on software repositories. In the first stage, they fine-tune a Transformer-based objective classifier. In the second stage, they train the priority detection model.
</br>
Image below is a overall architecture of the proposed approach:
<img width="642" alt="image" src="https://user-images.githubusercontent.com/59199865/212192597-509b2991-f77c-4d3c-a900-ffcce975d38a.png">

## FineLocator: A novel approach to method-level fine-grained bug localization by query expansion

In this paper they proposed an approach called FineLocator for method-level fine-grained bug localization by query expansion. They use word vector and TF-IDF to initialize the vector representation of bug reports and source code methods. Considering the sparseness in the representation of methods caused by its short lengths, they augment a method with its neighboring methods by query expansion. Specifically, semantic similarity, temporal proximity and call dependency are taken into account in measuring the neighboring relations between methods.
</br>
Image below is a overall architecture of the proposed approach:
<img width="812" alt="image" src="https://user-images.githubusercontent.com/59199865/212193828-05d8f7e7-2b07-4e36-96bd-a7a383cf849c.png">
