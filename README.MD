Download from git or <git clone https://github.com/panostraf/RecSys.git>
pip install -r requirements.txt



In order to properly run the models, first execute data_cleaning.ipynb and clustering.ipynb
they will create the dependencies

rfc_model.ipynb must be executed before keras_model.ipynb
It will create a dataset to train the keras model, with the embeddings of the sessions
