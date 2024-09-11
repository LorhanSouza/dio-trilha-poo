classDiagram
    iPhone -- |> ReprodutorMusical
    iPhone -- |> AparelhoTelefonico
    iPhone -- |> Navegador
    class ReprodutorMusical{
      +selecionarMusica(String musica)
      +tocar()
      +pausar()
    }
    class AparelhoTelefonico{
      +ligar(String numero)
      +atender()
      +iniciarCorreiodeVoz()
    }
    class Navegador{
      +exibirPaginas(String url)
      +adicionarNovaAba()
      +atualizarPagina()
    }