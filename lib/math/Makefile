# SPDX-License-Identifier: GPL-2.0-only
obj-y += div64.o gcd.o lcm.o int_pow.o int_sqrt.o reciprocal_div.o

obj-$(CONFIG_CORDIC)		+= cordic.o
obj-$(CONFIG_PRIME_NUMBERS)	+= prime_numbers.o
obj-$(CONFIG_RATIONAL)		+= rational.o
obj-$(CONFIG_MEAN_AND_VARIANCE) += mean_and_variance.o

obj-$(CONFIG_TEST_DIV64)	+= test_div64.o
obj-$(CONFIG_RATIONAL_KUNIT_TEST) += rational-test.o
obj-$(CONFIG_MEAN_AND_VARIANCE_UNIT_TEST)   += mean_and_variance_test.o
