```c
#include <stdio.h>

typedef struct {
    const char* cargo;
    const char* empresa;
    const char* periodo;
    const char* atividades[];
} Experiencia;

int main()
{
    // Informações Pessoais
    const char* nome = "Pablo Ribeiro";
    const char* faculdade = "PUC Goiás";
    const char* curso = "Ciências da Computação";
    const char* periodo = "2º Período";
    const char* interesses[] = {"Programação", "Jogos", "Músicas"};
    const char* linguagem_principal[] = {"C", "C++"};

    // Habilidades e Estudos
    const char* estudos_progresso[] = {"Estrutura de Dados", "Desenvolvimento de Jogos na Unity"};
    const char* habilidades_concluidas[] = {"Algoritmos Básicos", "Desenvolvimento Web"};

    // Experiência Profissional
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
