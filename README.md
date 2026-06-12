# Add-Gradient-Clipping-to-a-Training-Loop

# Findings:
#
# A deep neural network was trained on the MNIST dataset with and without
# gradient clipping. Without clipping, the loss remained high throughout
# training and showed limited improvement, indicating unstable parameter
# updates caused by large gradients.
#
# After applying gradient clipping with a maximum norm of 1.0, the loss
# decreased steadily from approximately 0.60 to 0.08 over five epochs.
#
# This demonstrates that gradient clipping helps stabilize training by
# preventing excessively large gradient updates, resulting in faster and
# more reliable convergence.
