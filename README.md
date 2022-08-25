# Bengali Speech Recognmition

In this notebook Bengali Speech Recognition demo is presented. [DeepSpeech2](https://arxiv.org/abs/1512.02595) is an End-to-End Speech Recognition model which is used to train ASR in Bengali Language. [Mixed precision](https://www.tensorflow.org/guide/mixed_precision) is used for faster model training and faster inference on [Tensor Core](https://www.nvidia.com/en-us/data-center/tensor-cores/) enabled Nvidia GPUs. The model is trained on [Common Voice Bangla Dataset](https://arxiv.org/abs/2206.14053) for 20 epochs. WER is 40%. Further training will result in lower WER. Follow the notebook for demo result.


## Demo Result

Target:  `ইংরেজির সাথে সাথে তাদের হিন্দী ও সংস্কৃত শিক্ষা দেওয়া হতো।`

Prediction:  `ইংরেজির সাথসানে তাদের হিন্দি ও সংস্কৃত শিক্ষা দেওয়া হত।`

Word error rate:  `0.4`


----------------------------------------------------------------------
Target:  `চতুর্থ সপ্তাহ থেকে অবস্থার উন্নতি হতে থাকে,কিন্তু এই উন্নতির হারের কিছু হেরফের আছে।`

Prediction:  `চতুর্থ শপ্তা থেকে অবস্থার উন্নতি হতে থাকে কিন্তু এই উন্নতির হারে কিছু হেরফের আছে।`

Word error rate:  `0.3076`


----------------------------------------------------------------------
Target:  `নিষিদ্ধ আদেশ তৎক্ষণাৎ শহরের উপর চাপিয়ে দেওয়া হয়েছিল।`

Prediction:  `নিষিদ্ধ আদেশে তক্ষণাৎ শহরের উপর চাপিয়ে দেওয়া হয়েছিল।`

Word error rate:  `0.25`


----------------------------------------------------------------------
Target:  `প্রাতিষ্ঠানিক শিক্ষার জন্যে ছোটবেলা থেকেই তাকে সংগ্রাম করে চলতে হয়েছে।`

Prediction:  `প্রাতিষ্ঠানিক শিক্ষার জন্য ছোটবেলা থেগি়ে তাকে সংগ্রাম করে চলতে হযেছে।`

Word error rate:  `0.3`


----------------------------------------------------------------------
Target:  `এই সমিতির কয়েকটি স্থানে আদর্শ কৃষি উদ্যান ছিল।`

Prediction:  `এই সমিতির কয়েকটি স্থানের আদর্শ কৃষদ্দান ছিল।`

Word error rate:  `0.375`


----------------------------------------------------------------------