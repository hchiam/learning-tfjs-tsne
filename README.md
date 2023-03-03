# Learning [tfjs-tsne](https://github.com/tensorflow/tfjs-tsne)

Just one of the things I'm learning. https://github.com/hchiam/learning

Get **t-SNE** output coordinates with [`tfjs-tsne`](https://github.com/hchiam/tfjs-tsne) and visualization powered by [`tfjs-vis`](https://github.com/hchiam/tfjs-vis).

Great explanation of SNE vs t-SNE (vs UMAP - which sounds better than t-SNE): https://towardsdatascience.com/visualizing-your-embeddings-4c79332581a9 - basically UMAP is better than t-SNE is better than SNE (which is related to the order they were invented).

Integration note: because tfjs-tsne and tfjs-vis are unmaintained and rely on an old version of tfjs that conflicts with the version of tfjs that models like universal-sentence-encoder rely on, I recommend swapping tfjs-tsne with [umap-js](https://github.com/PAIR-code/umap-js#umap-js) and swapping tfjs-vis with [chart.js](https://github.com/chartjs/Chart.js) so they all play nice together. Apparently UMAP is better than t-SNE anyways.

## Starting by testing out this repo

Run `yarn global add parcel` or `npm install -g parcel`, and then:

Using [`yarn`](https://github.com/hchiam/learning-yarn): (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-template.git && cd learning-template && yarn;
yarn dev;
```

Or with `npm`: (triple-click to select all)

```bash
git clone https://github.com/hchiam/learning-template.git && cd learning-template && npm install;
npm run dev;
```

## notes to self

```sh
yarn deploy
```

https://tjfs-tsne-demo.surge.sh
