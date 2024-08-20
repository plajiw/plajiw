```c
// Sobre Mim
const char* nome = "Pablo Ribeiro";
const char* curso = "Ciências da Computação";
const char* universidade = "PUC Goiás";
const char* linguagens[] = {"C", "C++", "Python", "Java"};
const char* areas_estudo[] = {"Desenvolvimento de Jogos", "Estrutura de Dados", "Banco de Dados"};

// Experiência Profissional
typedef struct {
    const char* cargo;
    const char* empresa;
    const char* periodo;
    const char* atividades[];
} Experiencia;

Experiencia experiencia_profissional = {
    "Estagiário de Suporte",
    "Auvo",
    "Mar 2024 - Atual",
    {"Atendimento ao Cliente", "Consultas em Banco de Dados", "API"}
};

// Habilidades
typedef struct {
    const char* concluidos;
    const char* em_progresso;
} Habilidades;

Habilidades habilidades = {
    "Algoritmos em C",
    "Estrutura de Dados"
};
