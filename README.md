# A Distributed Online Learning Approach for Pattern Prediction over Movement Event Streams with Apache Flink


> Ehab Qadah, Michael Mock, Elias Alevizos, and Georg Fuchs. A Distributed
Online Learning Approach for Pattern Prediction over Movement Event Streams
with Apache Flink. In EDBT/ICDT Workshops, 2018.

### Abstract
<p>
In this paper, we present a distributed online prediction system for user-defined patterns over multiple massive streams of movement events, built using the general purpose stream processing framework Apache Flink. The proposed approach is based on combining probabilistic event pattern prediction models on multiple predictor nodes with a distributed online learning protocol in order to continuously learn the parameters of a global prediction model and share them among the predictors in a communication-efficient way. Our approach enables the collaborative learning between the predictors (i.e., "learn from each other"), thus the learning rate is accelerated with less data for each predictor. The underlying model provides online predictions about when a pattern (i.e., a regular expression over the event types) is expected to be completed within each event stream. We describe the distributed architecture of the proposed system, its implementation in Flink, and present experimental results over real-world event streams related to trajectories of moving vessels. </p>


## BibTeX citation:

```
@inproceedings{Qadah,
	title = {{A Distributed Online Learning Approach for Pattern Prediction over Movement Event Streams with Apache Flink}},
	author = {Qadah, Ehab and Mock, Michael and Alevizos, Elias and Fuchs, Georg},
	booktitle={EDBT/ICDT Workshops},
	year={2018}
}
```
