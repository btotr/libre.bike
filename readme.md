# libre.bike

Basistraining schema voor coaches en generatie van ramptest-rapport. 

## afhankelijkheden

Zorg ervoor dat [ConText](https://wiki.contextgarden.net/Installation) is geinstaleerd.
Op Ubuntu doe je dit met:

```
 apt-get install context
```

## basis training

De basis training is te vinden onder de map basistraining.  
Gebruik bijvoorbeeld [Golden Cheeta](https://www.goldencheetah.org/) om de trainingen in te laden   

## inspanningsverslag genereren

Doe een ramptest en verwerk de gegevens in 'inspanningstest/user.tex'

```
context ramptest.tex
```

Dit zal een [ramptest-rapport](https://github.com/btotr/libre.bike/files/9079287/ramptest.pdf) genereren om te delen
