from company_name_formatter import format_company_name

def test_valid_inputs():
    assert format_company_name("CAF softsol") == "CAF SoftSol India Pvt Ltd."
    assert format_company_name("CAF solution") == "CAF SoftSol India Pvt Ltd."
    assert format_company_name("CAF softSolution India Pvt Limited") == "CAF SoftSol India Pvt Ltd."

def test_empty_input():
    assert format_company_name("") == "Company name not provided"

def test_none_input():
    assert format_company_name(None) == "Company name not provided"

print("All test cases passed successfully!")