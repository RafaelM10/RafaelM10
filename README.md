<div align="center">

### Olá, devs! Sejam bem-vindos ao meu perfil 👋

Sou apaixonado por desenvolvimento de software, resolução de problemas e colaboração em equipe para criar soluções inovadoras.
</div>

```php
abstract class Apresentation {
 private $name;
 private $occupationArea;

 public function setName(string $rafaelMeira): string {
   $this->name = $rafaelMeira;
}
 public function setOccupationArea(string $fullstackDeveloper): string {
   $this->occupationArea = $fullstackDeveloper;
}

public function skills(): array {
   return [
        "frontend" => ["HTML", "CSS", "JavaScript", "React", "Typescript"],
        "backend" => ["PHP", "Node.js", "Typescript", "SQL"],
        "unitaryTests" => ["JEST", "PHPUNIT],
        "otherKnowledges" => ["Express", "Sequelize", "NestJS", "Swagger", "TypeORM", "JWT"],
        "database" => ["MySQL", "PostgreSQL", "MongoDB", "MariaDB"],
        "metodologia_agil" => ["Azure", "Scrum", "Kanban", "Jira"]
    ];
 }

public function getName(): string {
  return $this->name;
}
 public function getOccupationArea(): string {
   return $this->occupationArea;
}
}
