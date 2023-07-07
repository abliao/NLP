# 基于知识库问答系统的改进
自动问答系统是自然语言处理领域经典的问题。解决该问题的传统方法之一是将其分为命名实体识别(Named Entity Recognition，NER)和属性映射(Property Map)问题。由于知识库规模以及模型性能带来的限制，导致问答准确性和多样性不足，模型无法应对开放域(open-vocabulary)的问题。为了解决这些挑战，本研究从三个关键方面进行了改进。首先，我们对命名实体识别任务进行了改进，采用了BERT和GPT2模型以及CRF技术，提高了命名实体识别的性能，从而准确地识别对话中的实体，为后续的对话生成提供准确的上下文信息。其次，为了丰富对话数据集并解决知识库不足的问题，我们使用了ChatGPT模型，通过生成数量更多，知识更丰富的数据，完成对知识库的扩充，能够提供更多样和全面的信息。最后，我们选择了基于ChatGLM-6B模型的架构作为问答系统的基础，并利用P-Tuning v2技术进行微调。这种选择和微调过程旨在提高问答系统的性能和效率，并实现开放域问答的效果，使其能够在大规模对话数据上进行高质量的问答。
