# Proposta do lucerna-phone-android

O app Android do [`lucerna-phone`](https://github.com/EduardoSA8006/lucerna-phone): o lado do celular do protocolo próprio que substitui o KDE Connect. O espelhamento e o controle da tela ficam com o scrcpy, sem depender deste app.

O protocolo será definido junto com o `lucerna-phone`, e este app o implementa no celular.

## Em aberto

- A linguagem e a stack. Kotlin é o padrão do Android, mas não foi decidido.
- Tudo o que depende do protocolo, listado na proposta do `lucerna-phone`: funções, descoberta, pareamento e criptografia.
