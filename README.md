# Square-finder-with-break
print('Kvadrat topuvchi chit !')
question = 'Istalgan son kiriting: '
question  += ('Agar chitimni to\'xtatmoqchi bo\'lsangiz "toxta chit" deb yozing: ')

while True:
    qiymat = input(question)
    if qiymat == 'toxta chit':
        break
    else:
        print(float(qiymat)**2)
print('The end')
