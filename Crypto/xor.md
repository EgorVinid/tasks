# XOR
даём - VQC~VEh6Zg106Z}5wZ6kf5a4kbZgw555555x
решение: забрутить xor ключ, понять что он равен 5, получить флаг

# Флаг: STF{S@m3_b453_x0r_3nc0d1ng_br000000}

`
cipher = 'VQC~VEh6Zg106Z}5wZ6kf5a4kbZgw555555x'
for elem in cipher:
    print(chr(ord(elem)^5), end='')
`
