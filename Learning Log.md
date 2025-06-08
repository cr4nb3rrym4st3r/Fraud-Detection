Started with research into datasets. Found the PaySim dataset (Payment Simulator) and a dataset which follows the same format which also has a trained model attached https://huggingface.co/datasets/CiferAI/Cifer-Fraud-Detection-Dataset-AF

Googled 'google colab cifer-fraud-detection-k1-a' found https://colab.research.google.com/github/feast-dev/feast-fraud-tutorial/blob/master/notebooks/Fraud_Detection_Tutorial.ipynb
Discovered feast 

Googled 'feast fraud detection on aws' found https://aws.amazon.com/blogs/opensource/getting-started-with-feast-an-open-source-feature-store-running-on-aws-managed-services/
![aws](https://awsopensourceblog.s3.us-east-2.amazonaws.com/assets/phi_feast/phi-feast_f1_1000x500.png)

Feast (Feature Store) is an ML data hub that solves one big problem. 

Essentially it used for using the same features (input data) for training models and making real time predictions without rebuilding pipelines.

We used AI to get the anology of feast for us to understand it better which one was:
**Feast is Your Restaurant’s Centralized Kitchen System**
**Menu (Feature Views)**
The menu lists all dishes (features) like “Spicy Salad” or “Steak.”
Each dish has a standardised recipe (feature definition) so every chef cooks it the same way.

**Ingredients Storage**
Walk-in Freezer (Offline Store):
Stores bulk ingredients (historical data) for meal prep (model training).
Example: Pre-chopped onions (user’s avg_spend_last_year).

**Countertop Fridge (Online Store):**
Holds fresh, ready-to-use ingredients (real-time data) for orders (predictions).
Example: Sliced tomatoes (user’s last_5_clicks).

**Chefs (ML Models)**
They don’t care where ingredients come from—just shout:
“I need ‘User Lifetime Value’ diced, stat!”
Feast (your kitchen system) delivers the same ingredient every time, whether from the freezer or fridge.

**Orders (Predictions)**
**Batch Catering (Training)**:
Grab 100 lbs of onions from the freezer (offline store) to prep for a wedding (train a model).

**À La Carte (Real-Time)**:
“Table 3 needs fries!” → Grab prepped potatoes from the countertop (online store) in seconds.

**Consistency Rule**
No Matter Who Cooks:
The “Spicy Engagement Salad” tastes identical whether made for rehearsal (training) or a live order (prediction).

**No Duplicate Work**:
You don’t hire one chef to chop onions for catering and another for dine-in—Feast chops once and supplies both.


