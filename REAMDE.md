# Saeed Matrix Calculation

Saeed Matrix Calculation is a Python library for adding, subtracting, multiplying, inverting matrices.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install SaeedMatrixCalculation.

```bash
pip install SaeedMatrixCalculation
```

## Usage

```python
from SaeedMatrixCalculation import Matrix

matrix_one = Matrix(3, 3, [[1,1,1], [1,1,1], [1,1,1]])
matrix_two = Matrix(3, 3, [[1,1,1], [1,1,1], [1,1,1]])

print(matrix_one + matrix_two)
print(matrix_one - matrix_two)
print(matrix_one * matrix_two)
print(matrix_one.invert_matrix())
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)