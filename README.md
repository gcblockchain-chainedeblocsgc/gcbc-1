# gcbc
Government of Canada Blockchain Codefest

__Cryptocurrencies as enablers of Large Scale Criminal Activities__

__Files:__

- Anomalous Activity in the Bitcoin Blockchain.pdf - Explanatory Presentation
- BlockChain Features2.ipynb - Notebook producing the charts in the presentation
- BlockSci Demo.ipynb - Demo notebook testing the BlockSci software

__Aim__

To use Machine Learning to study patterns publicly visible in the bitcoin blockchain to identify indicators of large-scale fraud, cyber ransomware attacks or other indicators of use for public safety, safety response or other public policy implementations.

__Background__

All bitcoin transactions are stored anonymously in the bitcoin blockchain. Individual addresses (payment endpoints) and transactions can be explored using existing tools, e.g. blockchain.info. Machine learning approaches look for patterns in the blockchain as a whole - features of blocks, transactions, or address payment histories that may be markers of criminal activity.

__Approach__

The BlockSci package for python (see https://github.com/citp/BlockSci/ ) allows the bitcoin blockchain to be indexed and accessed programmatically for feature extraction. Workflow is to develop a set of potential features, and use python tools  to examine look for outliers and examine suspect blocks or transactions. Please see the accompanying presentation for more details.

__So far:__ BlockSci up and running on AWS, validation against blockchain.info to look at some transactions
Some demo code and output is posted here, but needs the BlockSci AMI running on Amazon AWS (or another install of BlockSci) in order to be run. Please get in touch if you need help setting this up.

Built a custom data-science AWS install of BlockSci.

Extracted and examined features for blocks and transactions from the bitcoin blockchain (See the BlockChain Features 2 notebook and accompanying presentation).

__ToDo:__ Add documentation for getting the AWS install up and running
