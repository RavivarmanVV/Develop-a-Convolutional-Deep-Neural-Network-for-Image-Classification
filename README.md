# Develop a Convolutional Deep Neural Network for Image Classification

## AIM
To develop a convolutional deep neural network (CNN) for image classification and to verify the response for new images.

##   PROBLEM STATEMENT AND DATASET
Include the Problem Statement and Dataset.

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 
Import the required libraries (torch, torchvision, torch.nn, torch.optim) and load the image dataset with necessary preprocessing like normalization and transformation.

### STEP 2: 
Split the dataset into training and testing sets and create DataLoader objects to feed images in batches to the CNN model.

### STEP 3: 
Define the CNN architecture using convolutional layers, ReLU activation, max pooling layers, and fully connected layers as implemented in the CNNClassifier class.

### STEP 4: 
Initialize the model, define the loss function (CrossEntropyLoss), and choose the optimizer (Adam) for training the network.

### STEP 5: 
Train the model using the training dataset by performing forward pass, computing loss, backpropagation, and updating weights for multiple epochs.

### STEP 6: 
Evaluate the trained model on test images and verify the classification accuracy for new unseen images.

## PROGRAM

### Name:

### Register Number:

```python
class CNNClassifier(nn.Module):
    def __init__(self, input_size):
        super(CNNClassifier, self).__init__()
        #Include your code here

    def forward(self, x):
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer
model =
criterion =
optimizer =

# Train the Model
def train_model(model, train_loader, num_epochs=3):

    # write your code here

        
        
        
        print('Name:        ')
        print('Register Number:       ')
        print(f'Epoch [{epoch+1}/{num_epochs}], Loss: {running_loss/len(train_loader):.4f}')

```

### OUTPUT

## Training Loss per Epoch

<img width="342" height="163" alt="image" src="https://github.com/user-attachments/assets/0a6a3c6e-2627-4184-a989-0f745282238a" />

## Confusion Matrix

<img width="847" height="650" alt="image" src="https://github.com/user-attachments/assets/39c521de-62cf-4c78-9d19-1e6186ddf680" />

## Classification Report
<img width="587" height="326" alt="image" src="https://github.com/user-attachments/assets/234e4ebe-572f-4a92-9344-cccd9ecffd95" />

### New Sample Data Prediction
<img width="598" height="464" alt="image" src="https://github.com/user-attachments/assets/1512a25a-2d88-4b34-a223-4a1a00106165" />

## RESULT
Thus, To develop a convolutional deep neural network (CNN) for image classification and to verify the response for new images is executed and verified successfully.
