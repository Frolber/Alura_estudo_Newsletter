# Estudo sobre o CSS Tailwind - aprendi no Alura

* O Tailwind é um framework para CSS que permite a criações de classes utilitárias.

* Surgiu por necessidade de facilidade e intuitiva, alta customização, tem integração com outros frameworks JS. Em que outros frameworks de CSS não tinha tanto assim.

* Foi construído em 2017.

* Tu estiliza os componentes direto nas classes dentro das TAG. Conhecidas commo classes utilitárias, as classes representam propriedades do CSS.

* Segue o site da TailwindCSS para acessar de como instalar e toda a documentação do Framework [TailwindCSS](https://tailwindcss.com/docs/installation).

* No momento que tu instala o Framework, já acontece a ação do Preflight que trabalha como se fosse um reset.css para tirar as inconsistências de estilos entre os navegadores.

## Vantagens

1. Não se preocupar muito com nomes das classes dos elementos.

2. Facilidade na estilização e não ter que lidar com arquivo.css

3. Mais fácil fazer mudanças.

4. Construa um layout com ajuda de estilos pré definidos mas que tenham uma leque enorme de possibilidades.

## Customização

É possível customizar do seu jeito algumas coisas, portanto precisa abrir a TAG script depois da primeira script padrao do Tailwind CSS.

Ficará dessa forma:

```html
<script>
         tailwind.config = {
            theme: {
               extend: {
                  colors: {
                     azul: {
                        claro: "#c5dfff",
                        escuro: "#061e3c",
                        hover: "#1057b0",
                     },
                  },
               },
            },
         };
      </script>
```

* O extend é importante estar se precisa manter as configurações padrão do framework. Caso contrário, existiria só as três cores acima.
