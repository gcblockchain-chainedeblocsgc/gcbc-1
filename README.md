# gcbc
Government of Canada Blockchain Codefest

__Cryptocurrencies as enablers of Large Scale Criminal Activities__

__Aim__

To use Machine Learning to study patterns publicly visible in the bitcoin blockchain to identify indicators of large-scale fraud, cyber ransomware attacks or other indicators of use for public safety, safety response or other public policy implementations.

__Background__

All bitcoin transactions are stored anonymously in the bitcoin blockchain. Individual addresses (payment endpoints) and transactions can be explored using existing tools, e.g. blockchain.info. Machine learning approaches look for patterns in the blockchain as a whole - features of blocks, transactions, or address payment histories that may be markers of criminal activity.

__Approach__

The BlockSci package for python allows the bitcoin blockchain to be indexed and accessed programmatically for feature extraction. Workflow is to develop a set of potential features, and use python tools (sci-kit learn, etc.) to examine their predictive power for flagging known criminal activity.

__So far:__ BlockSci up and running on AWS, validation against blockchain.info to look at some transactions
Some demo code and output is posted here, but needs the BlockSci AMI running on Amazon AWS (or another install of BlockSci) in order to be run. Please get in touch if you need help setting this up.

Updated to add some examples of feature extraction from the Bitcoin blockchain

__ToDo:__ Building a custom data-science AWS install of BlockSci (almost done)

Additional feature extraction and comparison with known flagged transactions/activities  - more to come, input is welcome
