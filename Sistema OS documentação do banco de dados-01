use dbinfox;
-- inspecionar tabelas no banco de dados
show tables;
-- o código abaixo cria uma tabela
create table tb_cliente(
idcli int auto_increment primary key,
cpfcli varchar(50) unique,
nomecli varchar(50) not null,
cep varchar(50) not null,
tipo varchar(50)not null unique,
logradouro varchar(50) not null,
numero varchar(50) not null,
complemento varchar(50),
bairro varchar(50) not null,
cidade varchar(50) not null,
uf varchar(2) not null,
fone1 varchar(50) not null,
fone2 varchar(50),
emailcli varchar(50) not null
);
show tables;
-- descrevendo a tabela
describe tb_cliente;
-- inserindo dados na tabela (Create)
insert into tb_cliente values
(null,'469.422.655/32','Geovani Matheus Bandeira','08568-300','Avenida Adutora','Adutora','622','oioioi','Jardim Nova Poá','Poá','SP','4638-0052','6969-6969','GMBandeira01@hotmail.com');

insert into tb_cliente values
(null,'555.845.682/55','Fabricio Ferreira de Oliveira','1515-5525','Palete','Houter','12','mestre','Pokemon','Rota 8','SP','8889-1528','6815-5456','FAFA@gmail.com');

insert into tb_cliente values
(null,'546.484.585-30','Victor Guilherme Leite de Medeiros','05814-548','San Diego','San Diego','456','San Diego','San Diego','San Diego','AM','8588-5282','5858-1456','VictorLeite@hotmail.com');

insert into tb_cliente values
(null,'486.546.545-30','Bruno Rodrigues','48415-549','summoners rift','summoners rift','summoners rift','summoners rift','summoners rift','summoners rift','KG','4158-4855','4598-8456','X1@outlook.com');

insert into tb_cliente values
(null,'454.556.548-55','Glauco Vinicius Bandeira','08568-300','Avenida Adtora','Adtora','632','ooioi','Jardim ova Poá','Pá','SP','4639-0052','9696-9696','GlaucoBandeira@outlook.com');

delete from tb_cliente where idcli = 1;
select * from tb_cliente;


use dbinfox;
-- inspecionar tabelas no banco de dados
show tables;
-- o código abaixo cria uma tabela
create table tb_usuarios(iduser int primary key,
usuario varchar(50) not null,
login varchar(50) not null unique,
senha varchar(50) not null,
fone varchar(15),
perfil varchar(50) not null);
show tables;
-- descrevendo a tabela
describe tb_usuarios;
-- inserindo dados na tabela (Create)
insert into tb_usuarios values
(1,'Geovani Matheus Bandeira','gmbandeira','oioioi','91111-1111','Aluno do Senac');
insert into tb_usuarios values
(2,'Victor Leite','victorl','victor','92222-2222','Aluno do Senac');
insert into tb_usuarios values
(3,'Fabricio Ferreira','fafa','fafa123','93333-3333','Aluno do Senac');
-- pesquisando dados na tabela (Read)
select * from tb_usuarios;



