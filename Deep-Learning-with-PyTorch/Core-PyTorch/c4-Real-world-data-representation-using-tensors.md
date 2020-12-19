- Having a good sense of how to perform operations on tensors and **index them effectively** is central to using tools like PyTorch successfully.

### 復習

- In general, PyTorch expects data to be laid out along specific dimensions **according to the model architecture** - for example, **convolutional versus recurrent**.
- Thanks to how the PyTorch libraries interact with the Python standard library and surrounding ecosystem, loading the most common types of data and converting them to PyTorch tensors is convenient.
- Converting spreadsheets to tensors can be very straightforward.
  - Categorical- and ordinal-valued columns should be handled differently from interval-valued columns.
- Text or categorical data can be encoded to a one-hot representation through the use of **dictionaries**.
  - Very often, embeddings give good, efficient representations.