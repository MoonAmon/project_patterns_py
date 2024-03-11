# Princípios do design orientado a objetos

## Princípio do aberto/fechado

Determina que classes ou objetos e métodos devem estar aberto para extensão, mas fechados para modificações.

**Vantagens:**

- As classes existentes não são alterados e, desse modo, as chances de regressão são menores.
- Ajuda a manter a compatibilidade com versões de códigos anteriores.

## Princípio da inversão de controle

Determina que módulos de alto nível não devem ser dependentes de módulos de baixo nível; ambos devem ser dependentes de abstrações. Os detalhes devem depender das abstrações, e não o inverso.

**Vantagens:**

- O alto acoplamento entre módulos deixa de ser predominante e, portanto, não há complexidade/rigidez no sistema.
- Como há uma camada evidante de abstração entre os módulos dependentes (proporcionada por um hook **(gancho)** ou um parânmetro), é fácil lidar com dependências entre os módulos de uma forma mais conveniente.

## Princípio da segreção de interfaces

Conforme determina o princípio de segreção de interfaces, os clientes não ser forçadaos a depender de interfaces que não utilizam.

**Vantagens:**

- Ele força os desenvolvedores a escrever interfaces enxutas e a ter métodos que sejam específicos da interface.
- Ajuda você a não encher as interfaces com métodos indesejados.

## Princípio da responsabilidade única

Conforme determina o príncipio da responsabilidade única, uma classe deve ter apenas um motivo para mudar.

**Vantagens:**

- Sempre que houver uma mudança em uma funcionalidade, essa classe em particular deverá ser alterada, e nada mais.
- Além disso, se uma classe tiver várias funcionalidades, as classes dependentes deverão passar por mudanças em razão de diversos motivos, o que deve ser evitado.

## Princípio da substituição

Determina que classes derivadas devem ser capazes de substituir totalmente as classes-base.

-----

# Conceito de padrões de projetos

As principais caracteristicas dos padrões de projetos são estas:

- São independentes de linguagem e podem ser implementados em linguagens diferentes.
- São dinâmicos, e novos padrões são introduzidos ocasionalmente.
- São passíveis de personalização e, portanto, são úteis aos desenvolvedores.

## Vantagens dos padrões de projeto

As vantagens dos padrões de projetos são estas:

- Os padrões são reutilizáveis em vários projetos.
- Problemas no nível de arquitetura podem ser solucionados.
- Os padrões resistiram ao teste do tempo e sua eficácia foi comprovada, pois incluem a experiência dos desenvolvedores e arquitetos.
- Apresentam confiabilidade e podemos contar com eles.
  
## Classificando os padrões

Exitem 3 categorias principais para os padrões de projetos são estes:

- padrões de criação;
- padrões estruturais;
- padrões comportamentais.



