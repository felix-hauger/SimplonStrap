# SimplonStrap

# Library of css files for Marsians of Marseille
#
# .Class names
# Recursive classes have at least two class names : litteral and compressed
# Ex : paddingleft-s ---> pl-s
#
#
#
#
# . Reset css
#
#
#
#
#
#
#
#
#
# . classes for control margin/padding of html elements, work like : 'property precision value' or 'property value' if precision not needed.
# Properties: margin, padding, border
# Precisions: top, right, bottom, left, ax(axe x), ay(axe y)
# Values: -l(large), -m(medium), -s(small).
# Ex: for a small padding to the right : paddingright-s(or pr-s) ; for a general large margin : margin-l(or m-l)
# others: .center: auto margin axe x to use for center a main related to body, for exemple
#
#

# SimplonStrap
#
# Library of css files by & for Marsians of Marseille
#
#
#
# ---- grid
# 12-columns-type grid, with various fractionned column sizes
# container class: .grid
# column dimensions: w-dividend-divider
# Exemples:
# 1 twelth column = w-1-12 = one-twelve
# 1 tier column = w-1-3 = w-4-12 = four-twelve
# 50% column = w-1-2 = w-2-4 = w-3-6 = w-6-12 = six-twelve
# For personalize your own grids, my advice is to use their greatest common divisor class names
# If you want to make a grid with a 7/12 and a 5/12 size columns, you should put 'w-7-12' and 'w-5-12' columns
# If you just want one separate in 1 tier and 2 tiers size columns, you may use 'w-1-3' and 'w-2-3'
