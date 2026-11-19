<div align="center">

<img src="assets/capa.svg" alt="Meu Jeitinho — uma flor delicada em tons de rosa e lavanda" width="760">

<img src="assets/icone_oficial.svg" alt="Ícone oficial do Meu Jeitinho" width="150">

### Um cantinho para acompanhar cada fase, com carinho e simplicidade.

**🌷 Android &nbsp; · &nbsp; 📴 Offline &nbsp; · &nbsp; 📅 Calendário &nbsp; · &nbsp; 💗 Diário pessoal**

<sub>Portfólio do aplicativo · Versão documentada: 1.0.4 · build 138</sub>

</div>

---

## 💌 Como nasceu

Criei o **Meu Jeitinho** pensando na minha filha. Ao procurar um aplicativo para uma pré-adolescente começar a acompanhar o ciclo menstrual, encontrei opções que incluíam assuntos e campos sobre sexualidade e gravidez. Eu queria, para este momento da vida dela, uma experiência mais simples, acolhedora e adequada ao que nossa família precisava.

Daí nasceu um espaço para registrar datas, sentimentos e pequenas anotações do dia a dia. A proposta é ajudar a Laurinha a se organizar e se conhecer, no seu tempo, com privacidade e sem publicidade.

> 🌸 **Uma ideia de pai:** tecnologia também pode ser um gesto de cuidado.

## ✨ O que o aplicativo oferece

| Recurso | Para que serve |
|:---|:---|
| 📅 Calendário | Acompanhar os dias registrados e consultar o ciclo |
| 🌷 Histórico | Rever datas de início e término dos ciclos |
| 💭 Sentimentos e mini diário | Guardar como foi o dia e escrever pequenas anotações |
| 🔔 Lembretes de cuidado | Durante um ciclo em andamento, o app pode exibir lembretes locais de cuidado, conforme as permissões e configurações do aparelho |
| 🗓️ Aviso da próxima previsão | Quando houver previsão calculada, pode avisar às 9h do dia anterior à data estimada |
| 💾 Backup local | Exportar e restaurar os dados por meio de um arquivo escolhido no celular |
| 🔐 PIN e código dos responsáveis | Controlar o acesso ao aplicativo e oferecer recuperação do PIN |
| 🎨 Temas suaves | Escolher entre rosa, lavanda, pêssego e menta |
| 📴 Uso offline | Consultar e registrar informações sem uma conta ou conexão com a internet |

O aviso da próxima previsão é **opcional**. Quando ativado, o aplicativo agenda uma notificação para as **9h do dia anterior** à data estimada e recalcula o agendamento quando a previsão muda. A mensagem deixa claro que se trata apenas de uma previsão. As estimativas não substituem orientação de um profissional de saúde.

## 🎀 Feito para ser leve

O visual da versão 1.0.4 usa cores suaves, cartões com volume discreto, títulos com sombra leve e avatares de corpo inteiro. Na build 138, as imagens dos sentimentos ganharam um pouco mais de destaque, rótulos como “Muito feliz” e “Com cólica” passaram a aparecer completos, e o encerramento das animações foi corrigido para não sobrepor miniaturas. O diário também passou a inserir stickers exatamente na posição do cursor. O ícone oficial recebeu uma margem de segurança maior para evitar cortes em launchers Android.

<div align="center">

🌼 &nbsp; 🌷 &nbsp; 🌼

*Cada dia tem o seu jeito. Aqui, todos cabem com carinho.*

</div>

## 🔒 Cuidado com os dados

As informações ficam no dispositivo, e o aplicativo funciona offline. O backup é um **arquivo JSON criado no local escolhido pela pessoa**; ele inclui registros, anotações, PIN e código dos responsáveis. Esse arquivo deve ser guardado com cuidado, pois **não é criptografado**. Restaurá-lo substitui os dados atuais após confirmação.

O PIN ajuda a controlar o acesso pela interface, mas não deve ser entendido como criptografia dos dados. O aplicativo não usa sincronização automática. Saiba mais em [privacidade e limites](docs/privacidade.md).

## 🧩 Por dentro do projeto

| Tecnologia | Papel no aplicativo |
|:---|:---|
| Kotlin e Jetpack Compose | Telas e interações do Android |
| Material 3 | Componentes e temas da interface |
| Room | Armazenamento local dos ciclos e registros diários |
| DataStore | Preferências, PIN e configurações |
| Notificações Android | Lembretes locais de cuidado e aviso opcional um dia antes da previsão |
| Gradle | Organização e compilação do projeto Android |

**Base atual:** Meu Jeitinho **1.0.4**, build **138**, `minSdk 26` (Android 8.0) e `targetSdk 36`. A compilação foi validada com sucesso pelo GitHub Actions em 19/11/2026. A partir desta build, o projeto também passou a manter uma chave privada de assinatura persistente para futuras atualizações do APK.

## 👨‍👧 Concepção

**David dos Santos Boneli** idealizou o aplicativo, definiu suas necessidades, acompanhou o visual e orientou a evolução a partir do uso da família. A implementação e a documentação tiveram assistência de inteligência artificial.

## 📚 Sobre este repositório

Este repositório apresenta o projeto como **portfólio público**. O código-fonte, o APK, as capturas pessoais, os históricos e os backups não são publicados aqui. Os desenhos do aplicativo podem ser apresentados futuramente depois de uma revisão de privacidade e direitos.

Leia também [Privacidade e limites](docs/privacidade.md) e [Direitos](DIREITOS.md).

<div align="center">

---

Feito com carinho para a Laurinha. 🌷

</div>
