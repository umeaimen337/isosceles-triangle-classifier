# isosceles-triangle-classifier
def is_isosceles(base, side1, side2):
  """
  This function checks if a triangle is isosceles given its base and two sides.

  Args:
      base: The length of the triangle's base.
      side1: The length of one of the triangle's sides.
      side2: The length of the other triangle's side.

  Returns:
      True if the triangle is isosceles, False otherwise.
  """

  # Check for equilateral triangle (all sides equal)
  if base == side1 and base == side2:
    return True

  # Check for isosceles triangle (two sides equal)
  elif base == side1 or base == side2:
    return True

  else:
    return False

# Example usage
base = 10
side1 = 12
side2 = 12

if is_isosceles(base, side1, side2):
  print("The triangle is isosceles.")
else:
  print("The triangle is not isosceles.")

# UM-E-AIMEN ALEENA AND HUMZA NIAZ
