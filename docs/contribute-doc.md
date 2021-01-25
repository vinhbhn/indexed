---
id: contribute-doc
title: Contribution Guide
sidebar_label: Contribution Guide
---

## Collaborate with us

We aim for indexed.wtf to be a robust source for developers to utilize as a resource for research and development for Layer 2 solutions.

## Submit an Issue or PR to keep information up to date

### Issue (easiest)

Please open a new issue in the [Github Repo](https://github.com/raid-guild/indexed).

Navigate to "Issues" in the top nav and click the green "New Issue" button.

OR

### Fork the repo

Create a new branch and submit a PR:

```
Fork the repo in githhub
git clone <your-forked-repo>
cd indexed
git checkout -b <your-branch-name>
```

Please include AT LEAST the information below if requesting to add a new service/chain:

- Chain Name
- Chain Type (Plasma, ZKSNARK, etc)
- Average Tx Cost
- Consensus Mechanism (PoW, PoS)
- Max Transactions Per Second (TPS)
- Social media and community links

Using the Ethereum mainnet as an example, the data for the homepage table would look like:

```
Chain Name: Ethereum Mainnet
Chain Type: Ethereum
Average Tx cost (average): 29 gwei
Consensus: Proof of work (PoW)
Max TPS: 12.6
```

Pleae construct your submission in a way that such data is easily derived for addition to the table.

Feel free to include additional info and data!!!

## Dev Stuff

### React Libraries

We utilize the following react libraries:

- [react-modal](https://www.npmjs.com/package/react-modal)

- [react-data-table-component](https://www.npmjs.com/package/react-data-table-component)

### Doc Structure

All docs are written in markdown and can be found in the `docs/` directory.

Please update pertinent docs by creating a PR via the [official repo](https://github.com/raid-guild/indexed).

If creating a brand new doc page, please follow the naming and id conventions outlined in the docusaurus v2 docs, and make sure to include the new page in the `sidebars.js` file.

### Run Locally

```
git clone https://github.com/raid-guild/indexed

cd indexed/

yarn install

yarn start
```

[Docusaurus](https://v2.docusaurus.io/docs/)
