/usr/local/bin/python3.12 /Applications/PyCharm CE.app/Contents/plugins/python-ce/helpers/pycharm/_jb_pytest_runner.py --path /Users/sergey/qa_python/tests.py 
Testing started at 13:10 ...
Launching pytest with arguments /Users/sergey/qa_python/tests.py --no-header --no-summary -q in /Users/sergey/qa_python

============================= test session starts ==============================
collecting ... collected 11 items

tests.py::TestBooksCollector::test_add_new_book_add_two_books PASSED     [  9%]
tests.py::TestBooksCollector::test_add_new_book_add_two_books_negative_input[qqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqq] PASSED [ 18%]
tests.py::TestBooksCollector::test_add_new_book_add_two_books_negative_input[ ] PASSED [ 27%]
tests.py::TestBooksCollector::test_set_book_genre_success PASSED         [ 36%]
tests.py::TestBooksCollector::test_get_book_genre_success PASSED         [ 45%]
tests.py::TestBooksCollector::test_get_books_with_specific_genre_success PASSED [ 54%]
tests.py::TestBooksCollector::test_get_books_genre_success PASSED        [ 63%]
tests.py::TestBooksCollector::test_get_books_for_children_genre_with_age_rating PASSED [ 72%]
tests.py::TestBooksCollector::test_add_book_in_favorites_success PASSED  [ 81%]
tests.py::TestBooksCollector::test_add_book_in_favorites_add_two_books PASSED [ 90%]
tests.py::TestBooksCollector::test_delete_book_from_favorites_success PASSED [100%]

============================== 11 passed in 0.01s ==============================

Process finished with exit code 0