# Practic
dct = {
	1: {
		1: 11,
		2: 12,
		3: 13,
	},
	2: {
		1: 21,
		2: 22,
		3: 23,
	},
	3: {
		1: 24,
		2: 25,
		3: 26,
	},
}
totasl = 0
for i in dct.values():
    for number in i.values():
        totasl+=number
print(totasl)
