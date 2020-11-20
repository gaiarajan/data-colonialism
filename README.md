# Data Colonialism

[In a famous incident](https://www.theverge.com/2018/1/12/16882408/google-racist-gorillas-photo-recognition-algorithm-ai), a Google photos identification algorithm identified a disproportionate number of Black people as "gorillas". See below(image from WSJ):

![Misidentification example](https://i.dailymail.co.uk/i/pix/2015/07/01/13/2A23A22200000578-0-image-a-54_1435753933706.jpg)

The company later [released a statement](https://www.businessinsider.com/google-tags-black-people-as-gorillas-2015-7) saying they were "appalled" at the mistake. Company reps asserted:

> We’re appalled and genuinely sorry that this happened. There is still clearly a lot of work to do with automatic image labeling, and we’re looking at how we can prevent these types of mistakes from happening in the future.

This answer doesn't acknowledge the misidentification's roots in systemic racism, likely because it'd compromise Google's brand image. Google "fixed" the problem of misidentification by blocking all primates from the tagging service. This solved the public-facing problem, but didn't address the underlying issue. Questions of data colonialism and ethics continued to swirl around the development community. This identification blunder was widely seen as a case of algorithmic racism— because the model was not trained on enough BIPOC, it failed to identify faces at the same accuracy as it did for hegemonic(white, cis) faces.

Could a larger, more diverse dataset mitigate the issue by teaching the algorithm to consider non-hegemonic faces?

If this were true, developers' main inclusion goal should be to accrue as wide and varied a dataset as possible. More diversity, in this frame of thought, is equivalent to more algorithmic inclusion, and objective good. If an algorithm "has all the info," it must be unbiased, inclusive, and therefore anticolonial.

However, I will challenge that by stating that the manner in which data is collected is important to establishing the data as a representative of a larger colonial violence, or an agent against it. Even inclusion can pose real risks of data colonialism: the goal of creating a numerically unbiased dataset may push developers to disregard issues of consent and power. For example, [Google allegedly targeted dark-skinned homeless people for facial photos to add to a training dataset for the Pixel 4](https://www.insider.com/google-allegedly-targeted-face-scans-of-dark-skinned-homeless-people-2019-10). The obvious financial and power differential of this interaction raises questions of consent. Did the dark-skinned homeless people targeted for this initiative have full information as to how their data was to be used? Did their financial situation—and the tiny $5 honorarium offered to them—create inappropriate coercion? It's impossible to answer these questions for sure. However, this second situation demonstrates that simply creating a "fair dataset" is insufficient— in order to be truly anticolonial, developers need to consider the actual communities they work with.
