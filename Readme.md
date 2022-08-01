How to run with the stub a.pyi:


```python -m pytype.single --imports_info /Users/alcides/Desktop/pytype_tests/.import_info --module-name ex --platform darwin -V 3.9 -o /Users/alcides/Desktop/pytype_tests/.pytype/pyi/ex.pyi --analyze-annotated --nofail --quick /Users/alcides/Desktop/pytype_tests/ex.py```