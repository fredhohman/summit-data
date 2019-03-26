# Summit Data

*Summit: Scaling Deep Learning Interpretability by Visualizing Activation and Attribution Summarizations*

Summit is a an interactive system that summarizes and visualizes what features a deep learning model has learned and how those features interact to make predictions.
This repository contains the data used in the [Summit visualization][summit].

For the Summit visualization, go to [https://github.com/fredhohman/summit][summit].

### Data

All data in the context of InceptionV1 trained on ImageNet.

* `imagenet.json`: metadata for each class including aggregated activations
* `data/feature-vis/`: feature visualizations images 
	* `data/feature-vis/channel/`: channel feature visualizations
	* `data/feature-vis/diversity-0/`: 1/4 diversity feature visualizations
	* `data/feature-vis/diversity-1/`: 2/4 diversity feature visualizations
	* `data/feature-vis/diversity-2/`: 3/4 diversity feature visualizations
	* `data/feature-vis/diversity-3/`: 4/4 diversity feature visualizations
	* `data/feature-vis/dataset-p/`: positive dataset examples for each channel
* `data/attribution-graphs/`: attribution graphs for each class

***

## Live Demo

For a live demo, visit: 


## Installation

Download or clone this repository (*warning*: this repository is big (~1GB)):

```bash
git clone https://github.com/fredhohman/summit-data.git
```

## License

MIT License. See [`LICENSE.md`](LICENSE.md).


## Contact

For questions or support [open an issue][issues] or contact [Fred Hohman][fred].

[summit]: https://github.com/fredhohman/summit
[fred]: http://www.fredhohman.com
[issues]: https://github.com/fredhohman/summit-data/issues
