# CQC2020

CQC2020 is a theme-based Chinese classical poetry dataset. The feature of this dataset is that each sentence of the poem is associated with a theme word. The poems in the data set come from 23 eras (including ancient and modern eras of China, and transitional eras). The dataset contains poems written by 12587 different poets.

## Statistics

* Number of poems: 225957

* Genre of poems: Quatrain

## Format

The file is of JSON type, each line is a dictionary type, poem content and theme words are list type. The order of the theme words matches the order of the sentences in the poem. An example is as follows:

<pre><code>{"title": "咏梅送熊通政", "dynasty": "明", "author": "吴希贤", "poem": ["江南草色别来久", "梦绕梅花思不禁", "何似拂衣归去好", "小斋明月夜横琴"], "keywords": ["江南", "梅花", "归去", "明月"]}</code></pre>

## cite

If you use the CQC2020 dataset, please cite the source of the dataset.
