# Random_Forest_Classification
# I get my "X" and "y" prepared, so I can import "train_test_split" and make "train" and "test" 
# Next from "sklearn.preprocessing" import "StandardScaler" and prepare "future scaling" on my "X_train" and "X_test"
# So i get my """X_train = sc.fit_transform(X_train)""" and """X_test = sc.transform(X_test)"""
# And now from "ensemble" I import "RandomForestClassifier" and set numbers of "trees" at (10), also i set parameter "entropy" to boost my model
# Then i train my model """classifier.fit(X_train, y_train)"""
