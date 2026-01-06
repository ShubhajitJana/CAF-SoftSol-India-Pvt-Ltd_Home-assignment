def format_company_name(company_name):
    """
    Accepts a company name string and returns
    standardized company name: 'CAF SoftSol India Pvt Ltd.'
    """

    if company_name is None:
        return "Company name not provided"

    company_name = company_name.strip()

    if company_name == "":
        return "Company name not provided"

    return "CAF SoftSol India Pvt Ltd."