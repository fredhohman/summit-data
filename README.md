# Summit Data

Summit is an interactive system that scalably and systematically summarizes and visualizes what features a deep learning model has learned and how those features interact to make predictions.
This repository contains the data used in the [Summit visualization][summit].

For the Summit visualization, go to [https://github.com/fredhohman/summit][summit].


### Data

All data in the context of InceptionV1 trained on ImageNet.

* [`data/imagenet.json`][imagenet]: metadata for each class including aggregated activations
* `data/feature-vis/`: feature visualizations images 
	* [`data/feature-vis/channel/`][channel]: channel feature visualizations
	* [`data/feature-vis/diversity-0/`][diversity-0]: diversity feature visualizations (1/4)
	* [`data/feature-vis/diversity-1/`][diversity-1]: diversity feature visualizations (2/4)
	* [`data/feature-vis/diversity-2/`][diversity-2]: diversity feature visualizations (3/4)
	* [`data/feature-vis/diversity-3/`][diversity-3]: diversity feature visualizations (4/4)
	* [`data/feature-vis/dataset-p/`][dataset-p]: positive dataset examples for each channel
* [`data/ag/`][ag]: attribution graphs for each class

***

## Live Demo

For a live demo, visit: [fredhohman.com/summit][demo]


## Download

Download or clone this repository (*warning*: this repository is big (~1GB)):

```bash
git clone https://github.com/fredhohman/summit-data.git
```


## Resources

We use feature visualizations from [Feature Visualization, Distill 2017][fv], and [Lucid][lucid].


## License

MIT License. See [`LICENSE.md`](LICENSE.md).


## Contact

For questions or support [open an issue][issues] or contact [Fred Hohman][fred].

[summit]: https://github.com/fredhohman/summit
[demo]: https://fredhohman.com/summit/
[fred]: http://www.fredhohman.com
[issues]: https://github.com/fredhohman/summit-data/issues

[imagenet]: data/imagenet
[channel]: data/feature-vis/channel/
[diversity-0]: data/feature-vis/diversity-0/
[diversity-1]: data/feature-vis/diversity-1/
[diversity-2]: data/feature-vis/diversity-2/
[diversity-3]: data/feature-vis/diversity-3/
[dataset-p]: data/feature-vis/dataset-p/
[ag]: data/attribution-graphs/

[fv]: https://github.com/distillpub/post--feature-visualization
[lucid]: https://github.com/tensorflow/lucid
