import unittest
from arithmetic_arranger import arithmetic_arranger


class UnitTests(unittest.TestCase):
    def test_too_many_problems(self):
        actual = arithmetic_arranger([
            "44 + 815", "909 - 2", "45 + 43", "123 + 49", "888 + 40",
            "653 + 87"
        ],"True")
        expected = "Error: Too many problems."
        self.assertEqual(
            actual, expected,
            'Expected calling "arithmetic_arranger()" with more than five problems to return "Error: Too many problems."'
        )
    def test_arrangement(self):
        actual = arithmetic_arranger(
            ["3 + 855", "3801 - 2", "45 + 43", "123 + 49"],"False")
        expected = "not true"
        self.assertEqual(
            actual, expected,
            'to be not true'
        )
if __name__ == "__main__":
    unittest.main()
