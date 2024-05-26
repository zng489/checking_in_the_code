# checking_in_the_code

def filter_long_strings(strings):
  """
  Filters and returns strings with more than 10 characters from a list.

  :param strings: List of strings to filter.
  :return: List of strings with more than 10 characters.
  """
  return [s for s in strings if len(s) > 20 and not (s.startswith('NR') or s.startswith('NM'))]

    long_strings = filter_long_strings(df.columns)

  joined_list.extend(long_strings)
