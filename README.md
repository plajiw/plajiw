```c
#include <stdio.h>

int main()
{
    // Informações Pessoais
    const char* nome = "Pablo Ribeiro";
    const char* faculdade = "PUC Goiás";
    const char* curso = "Ciências da Computação";
    const char* periodo = "2º Período";
    const char* principais_interesses[] = {"Programação", "Jogos", "Músicas"};

    // Linguagens e Conhecimentos
    const char* linguagens_principais[] = {"C", "C++"};

    // Habilidades e Estudos
    const char* habilidades_concluidas[] = {"Algoritmos Básicos", "Desenvolvimento Web (HTML e CSS)"};
    const char* estudos_progresso[] = {"Estrutura de Dados", "Desenvolvimento de Jogos na Unity"};


    // Experiência Profissional
    typedef struct {
        const char* cargo;
        const char* empresa;
        const char* periodo;
        const char* atividades[];
    } Experiencia;

    Experiencia experiencias[] = {
        {
            "Estagiário de Suporte",
            "Auvo",
            "Mar 2024 - Atual",
            {"Atendimento ao Cliente", "Banco de Dados", "API"}
        }
    };

    return 0;
}

