Transcrição e Sumarização Automática de Vídeos
Este projeto utiliza ferramentas de Inteligência Artificial para realizar a transcrição e sumarização de vídeos de forma automatizada. Abaixo está o fluxo principal do processo:

Ferramentas Utilizadas:
Whisper (da OpenAI): Para transcrição de áudio.

Transformers (da Hugging Face): Para sumarização de texto.

Funcionalidades:
Download de Vídeo: Utilizando yt-dlp para baixar vídeos do YouTube.

Extração de Áudio: Usando moviepy para extrair o áudio dos vídeos baixados.

Transcrição de Áudio: Aplicando o modelo Whisper para transcrever o áudio em texto.

Sumarização de Texto: Utilizando a pipeline de sumarização para condensar o texto transcrito em resumos concisos.

Como Usar:

    Instale as Dependências:
        !pip install yt-dlp moviepy whisper transformers
        !apt-get install ffmpeg
        !pip install openai-whisper
    
    Execute o Script:
        RESUMINDO1.ipynb
    
    Insira a URL do Vídeo: Quando solicitado, insira a URL do vídeo que deseja processar.