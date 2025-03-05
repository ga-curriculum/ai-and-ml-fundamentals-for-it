<h1>
  <span class="headline">AI and ML Fundamentals for IT</span>
  <span class="subhead">Artificial Intelligence 101</span>
</h1>

**Learning objective:** By the end of this lesson, students will learn the core concepts of artificial intelligence (AI), be able to differentiate between narrow and general AI, and understand how AI systems differ from traditional programs.

## What is artificial intelligence (AI)?

AI aims to make computers mimic human thinking and decision-making, enabling them to tackle complex tasks that typically require human intelligence.

In other words, AI enables computers to simulate human cognitive abilities like learning, problem-solving, pattern recognition, and decision-making. This doesn't mean that the computer is actually thinking like a person, but it can handle tasks in a way that appears intelligent.

We broadly classify AI systems into two categories:

- **Narrow AI**: Focuses on specific tasks, like playing chess or recognizing speech. It is practical and in use today. They excel at the task they are designed for and can often outperform humans at that single task. However, narrow AI cannot think broadly or perform general cognitive abilities.

- **General AI or artificial general intelligence (AGI)**: AI with cognitive abilities that can handle any intellectual task. This is a not-yet-achieved form of AI that would be able to understand, learn, and apply knowledge across multiple domains, similar to how humans adapt to new situations.

Today's AI, as impressive as it is, is still narrow AI. When these AI systems make decisions, they do so based on patterns in data or deep knowledge of a specific domain rather than true understanding.

## How are AI systems different from regular programs?

As AI becomes more prevalent, it's important to understand how it differs from traditional programming.

### Traditional programming

To build a traditional program, a human programmer analyzes a problem and writes explicit instructions (rules) for the computer to follow. For example, to filter spam emails, a programmer might hard-code rules like "if an email's subject contains the word 'lottery' or 'prize', then mark it as spam."

This approach requires anticipating all possibilities and coding rules for each. It's effective for well-defined tasks but breaks down for complex problems with ambiguity (for example, recognizing a face in a photo or understanding natural language) because the programmer has to code millions of rules.

Computers historically relied on this kind of explicit, hand-crafted knowledge where everything had to be explicitly told to the machine.

### AI approach

To build an AI-powered app, the programmer creates a program to learn patterns from that data. They then *train* the system by showing it many examples.

> 📚 *Training* is the process of teaching an AI system to make predictions or decisions based on data. This training process results in a *model*, which is the final product of the training process. This model can then make decisions about new, unseen data.

For example, suppose you were building a system that can distinguish between spam emails and legitimate emails. In that case, you might train the system on a large dataset of emails labeled "spam" or "not spam" until it learns to recognize the difference.

The model automatically learns the characteristics of spam email from these examples (maybe it learns that spam often contains phrases like "winning prize" or odd sender addresses).

Later, given a new email, the model uses what it learned to predict whether it is spam. The key is that the computer figured out the rules by learning from examples, not because a human explicitly programmed those rules.

This approach shines in complex tasks like image recognition or language translation, where writing explicit rules is nearly impossible, but learning from data is feasible.

### Understanding the role of each

- Regular programs are *deterministic*, meaning they will always produce the same output for the same input. AI systems are *probabilistic*, meaning they may produce different outputs for the same input.
- Regular programs are *explicit*, meaning they follow a set of rules and instructions to perform tasks. AI systems are *implicit*, meaning they learn from data and adapt their behavior based on that experience.
- Regular programs are *static*, meaning they don't change unless a programmer modifies them. AI systems are *dynamic*, meaning they can learn and improve over time as they are exposed to more data.

<div class="activity discussion">
  <h2 class="title">Identify the benefits and risks of AI</h2>
  <span class="minutes">5 min</span>
</div>

With the above in mind, let's discuss the following questions:

- What are some benefits and risks of AI systems compared to regular programs?
- What can we do to help mitigate those risks when we use AI systems?
