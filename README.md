def main():
    """
    ##################################################
    Comlete your code here
    Use m_perc, f_perc, nb_perc for your results
    ##################################################
    """

    # Example: Assuming you have the counts of males, females, and non-binary individuals
    # Replace these with your actual calculations
    males = 10
    females = 15
    non_binary = 5
    total = males + females + non_binary

    m_perc = (males / total) * 100
    f_perc = (females / total) * 100
    nb_perc = (non_binary / total) * 100

    """
    ########################################
    # Do not delete the return statement
    ########################################
    """
    print(
        f'The percentage of males, females and non-binary \t {m_perc: .2f} \t {f_perc: .2f} \t {nb_perc: .2f}')
    return m_perc, f_perc, nb_perc


if __name__ == '__main__':
    main()
    