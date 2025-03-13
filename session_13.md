# Frequentist definition of probability
# Law of Large numbers
1. The law of large numbers states that the more experiments we run, the closer we will tend to get tot the expected probability
2. The Law of Large Numbers is a key principle in probability theory that provides a mathematical basis for the frequentist interpretation of probability. It asserts that as the number of trials or observations grows, the average of the observed results will approach the expected value, or theoretical mean.

# Events and Sample Spaces
1. Coin Toss example
- We have a fair coin with two outcomes: Heads (H) and Tails (T).
- The probability of getting Heads is 
p(H)=0.5
P(H)=0.5, and the probability of getting Tails is 
P(T)=0.5 P(T)=0.5.
- We toss the coin repeatedly and record the number of Heads.
![image](https://github.com/user-attachments/assets/275061bd-0756-4759-89d2-30c7daa9c04d)
3. Dice throwing example
  ![image](https://github.com/user-attachments/assets/74c22dc8-ba89-4b24-b18a-1239ffda5444)
  ![image](https://github.com/user-attachments/assets/91e4e2d2-dbac-4117-9377-83eedab09030)

# Dependent and Independent Events
1. Two events A and B are said to be dependent if the occurrence of one event affects the probability of the other event. In other words, knowing that one event has occurred provides information about the other event.
 ![image](https://github.com/user-attachments/assets/c29e0fef-1813-4619-92da-dd3f1a211a32)
2. Two events A and B are said to be independent if the occurrence of one event does not affect the probability of the other event. In other words, knowing that one event has occurred gives no information about the other event.
 ![image](https://github.com/user-attachments/assets/bcd3d156-b2bc-4894-aec4-39df387d992c)

# Joint probability
![image](https://github.com/user-attachments/assets/e02578cd-25f4-42cb-b829-86465c78bd8f)

# Marginal Probability
![image](https://github.com/user-attachments/assets/b6c8c223-9fa2-47b6-a32e-f1816fd56180)

# Conditional Probability
1. Similarity to Hypothesis testing
   ![image](https://github.com/user-attachments/assets/44280e0c-f9a8-4cbb-8f3f-628ce70485c4)

# Bayes theorem
![image](https://github.com/user-attachments/assets/18690b1c-7e3b-471f-ad42-8f0cbf8a701b)

1. Prior
2. Likelihood
3. Posterior
   ![image](https://github.com/user-attachments/assets/9208de8d-8f3c-4753-8d5d-870c8f8a106f)

# Difference between conditional probability and Bayes theorem
![image](https://github.com/user-attachments/assets/78ffdd39-7be9-49aa-8d32-ade3ceeb9c17)

# Expected value
The expected value is a fundamental concept in probability and statistics that represents the long-run average value of a random variable over many repetitions of an experiment.
![image](https://github.com/user-attachments/assets/7f3f242e-d4a4-49dd-b77b-5e4351ba7c45)

# Essense of Information theory
1. Quantifying uncertainity
2. Entropy
3. Entropy curve calculation
4. Cross entropy
   
# Problem 1: Medical Test Accuracy
A certain disease affects 1% of population. A test of the disease is 99% accurate meaning
1. If a person has the disease the test will be positive 99%
2. If the person does not have disease, the test will be negative 99%
P(D): Probability of person has disease P(T) : Probablity of test is positive
P(D) = 0.01
P(D′) = 1-$P(D)$ = 1-0.01 = 0.99
P(T|D) = 0.99
P(T′D′) = 0.99
P(T|D′) = 1-$P(T|D)$ = 1-0.99 = 0.01
Find P(D|T) and P(D|T′)
![image](https://github.com/user-attachments/assets/7d4b36bb-a956-41fc-84d0-444d3166511c)
![image](https://github.com/user-attachments/assets/47eeba63-8f5c-4b2b-93f0-e9f5580335cb)
![image](https://github.com/user-attachments/assets/ec19778e-1142-4f29-b0e9-93c3e297325d)
![image](https://github.com/user-attachments/assets/9040d464-6561-4091-9363-efec5973bb88)
![image](https://github.com/user-attachments/assets/67893a30-abc9-4e01-a2f1-cdd12d377bbf)
![image](https://github.com/user-attachments/assets/f783d60c-5e60-4c83-b00a-4178f00b634b)
![image](https://github.com/user-attachments/assets/166e9bf6-5525-4aae-a664-aa3bd0a4f013)
![image](https://github.com/user-attachments/assets/a1b3fcf2-6908-4f0d-a8b8-16f4640369f9)
![image](https://github.com/user-attachments/assets/f6ee702b-1e0d-4102-bbab-de3877fab5e0)

# Problem 2: Spam Email Classification
Suppose and email is classified as spam if it contains the word "money". Past statistics show:
1. 5% of all emails are spam
2. 2% non-spam emails contains the word money
3. 60% spam emails contains the word money
Find P(Spam|money) and P(Spam|money′)
![spam qs](https://github.com/user-attachments/assets/b3736669-d822-40d8-b93b-908580b62f06)

# Problem 3 : Sample Space
1. List the sample space for tossing two coins
2. What is the sample space for rolling two dice?
3. How many possible outcomes exist in selecting a card from a standard deck of 52 playing cards?
4. If an experiment consists of flipping a coin and rolling a die, what is the total number of outcomes?
   ![1](https://github.com/user-attachments/assets/e99a8d4c-dd27-4d1f-acb4-a3d4bf3dfa58)
   ![2](https://github.com/user-attachments/assets/8fdcb24d-2bb6-4470-86e7-204cac58ac5f)

# Problem 4 :Dependent and Independent Events**
1. A bag contains 4 red balls and 6 blue balls. If you pick one ball and then another with replacement, are the events independent or dependent?
   ![3](https://github.com/user-attachments/assets/35d45504-9c8c-4eb6-8e13-bebbe1767539)

# Problem 5: Joint and Marginal Probability**
1. A dataset shows that 40% of customers purchase Product A, 25% purchase Product B, and 15% purchase both. What is the probability that a customer purchases at least one product?
   ![4](https://github.com/user-attachments/assets/cc5a5ded-f8db-4a46-a25e-65fa342296e2)

# Problem 6: Expected Value**
1. A lottery ticket costs ₹10 and has a 1% chance of winning ₹500. What is the expected value of the ticket?**
   ![5](https://github.com/user-attachments/assets/7fa60eec-28c6-49e3-b007-0f499ebaa802)

# Problem 7: Entropy & Information Theory**
1. What is the entropy of a fair coin toss?**
![image](https://github.com/user-attachments/assets/25f928a5-f34d-4c85-b3c2-1d98b95f0ecd)
2. A probability distribution is P(X)=(0.8,0.2). Calculate its entropy
   ![6](https://github.com/user-attachments/assets/3abfc16a-e8bc-493a-81eb-6202380f306d)

