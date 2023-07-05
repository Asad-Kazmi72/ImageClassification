I trained a model on the popular MNIST dataset, but with a twist. Instead of using the original 28x28 grayscale images, I resized them to 32x32, converted them to RGB, and leveraged the power of EfficientNetB7 as the base model for feature extraction.

The model achieved impressive results even with just 3 training epochs, reaching an accuracy of 91.43% on the validation set!

I then fine-tuned the model by enabling training for both the custom layers and EfficientNetB7. The model further improved and achieved an impressive accuracy of 98.52% on the test set after 10 epochs!

