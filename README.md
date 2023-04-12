# Random_Forest_Classification
# I get my "X" and "y" prepared, so I can import "train_test_split" and make "train" and "test" 
# Next from "sklearn.preprocessing" import "StandardScaler" and prepare "future scaling" on my "X_train" and "X_test"
# So i get my """X_train = sc.fit_transform(X_train)""" and """X_test = sc.transform(X_test)"""
# And now from "ensemble" I import "RandomForestClassifier" and set numbers of "trees" at (10), also i set parameter "entropy" to boost my model
# Then i train my model """classifier.fit(X_train, y_train)""" and check prediction """classifier.predict(sc.transform([[30, 87000]]))"""
# Next i prepare my "y-pred" on "X_test" """y_pred = classifier.predict(X_test)""" and import "confusion_matrix"
# And "fit" into my "y_pred" and "y_test" """cm = confusion_matrix(y_test, y_pred)"""
# Finally i get my score """accuracy_score(y_test, y_pred)""" and visualize my results
