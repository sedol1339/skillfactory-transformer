Этом раздел закрепляет на практике понимание архитектуры "трансформер", которая была предложена группой исследователей из Google в 2017 году в статье [Attention Is All You Need](https://arxiv.org/abs/1706.03762).

Трансформер и его модификации получили широкое распространение в задачах NLP ([BERT](https://arxiv.org/abs/1810.04805), [ALBERT](https://arxiv.org/abs/1909.11942v6), [RoBERTa](https://arxiv.org/abs/1907.11692), [GPT](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf), [GPT-2](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf), [GPT-3](https://arxiv.org/abs/2005.14165), [ruGPT-3](https://sbercloud.ru/ru/warp/gpt-3), [Turing-NLG](https://www.microsoft.com/en-us/research/blog/turing-nlg-a-17-billion-parameter-language-model-by-microsoft/), [Switch Transformer](https://arxiv.org/abs/2101.03961), [EFL](https://arxiv.org/abs/2104.14690v1), [Reformer](https://ai.googleblog.com/2020/01/reformer-efficient-transformer.html), [T5](https://arxiv.org/abs/1910.10683) и много других). Языковые модели, основанные на трансформерах, способны генерировать [тексты](https://mobile.twitter.com/raphamilliere/status/1289129723310886912), почти неотличимые от написанных человеком. Трансформеры также начинают активно использоваться в компьютерном зрении ([ViT](https://arxiv.org/abs/2106.04803v2), [HRNet](https://arxiv.org/abs/1909.11065v6), [SwinIR](https://arxiv.org/abs/2108.10257) и др., см. также [здесь](https://habr.com/ru/post/578308/) и [здесь](https://arxiv.org/abs/2101.01169)), в мультимодальных сетях, связанных одновременно с изображениями и текстом ([CLIP](https://openai.com/blog/clip/), [DALL-E](https://openai.com/blog/dall-e/), [Wu Dao](https://www.forbes.com/sites/alexzhavoronkov/2021/07/19/wu-dao-20bigger-stronger-faster-ai-from-china/) и др.), и даже в предсказании структуры белков ([AlphaFold2](https://www.nature.com/articles/s41586-021-03819-2)). Более того, есть [работа](https://arxiv.org/abs/2103.05247), показывающая, что трансформер может претендовать на роль универсальной архитектуры для одновременного решения самых разных задач.

Мы пока не изучаем различные модификации трансформера, а изучаем только его оригинальный вариант. Для повторения теории вы можете использовать следующие материалы:

1. Материалы обучающего модуля курса NLP-инженер
1. Научную статью [Attention Is All You Need](https://arxiv.org/abs/1706.03762) (англ.)
1. Статью [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) (англ.) и [перевод на Хабре](https://habr.com/ru/post/486358/)
1. [Часть обучающего курса про трансформеры от Лены Войты](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html) (англ.)
1. [Практику по трансформерам от UvA Deep Learning Tutorials](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial6/Transformers_and_MHAttention.html) (англ.)
1. Экспертов поддержки в Slack, которым без вас скучно :)

Вы также можете прочитать [Детальное описание устройства трансформера](http://www.generalized.ru/Attention_Is_All_You_Need) от автора данного раздела.

Трансформер - непростая архитектура, и перед тем, как переходить к практике построения трансформеров, рекомендуется хорошо изучить принцип их устройства. Давайте повторим теорию.

### Вопрос 1

