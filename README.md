# SMILES_Sandwich_Transformer: De Novo Drug Design for predicting molecular properties

• Developed a Sandwich Transformer by reordering decoder sublayers (self-attention, cross-
attention, and feedforward) to improve molecular fingerprint learning from SMILES
sequences in drug discovery tasks.
• Pretrained the model on the ChEMBL-30 dataset and fine-tuned it on multiple molecular
property prediction tasks from the MoleculeNet benchmark, using a consistent MLP head
for evaluation.
• Performed comparative analysis against baseline SMILES Transformers and encoder
variants, where decoder-based sandwich models showed improved performance on 2 out
of 3 classification tasks like Blood-Brain Barrier, binding of b-secretase 1(BACE-1), and
inhibit HIV replication.
• Presentation video- https://www.youtube.com/watch?v=yGKWgv8Ng3Y
