# Spring_Data_JPA_JAVA

<h1> Sejam bem-vindos ao meu Projeto Spring Data JPA na Prática. </h1> 

<h3> Conhecendo Spring Data JPA na prática com Java. </h3>
Curso oferecido gratuitamente pela plataforma online <a href="https://dio.me/" rel="nofollow"><strong> Digital Innovation One</strong></a>

<h2 dir="auto"><a id="user-content--objetivo-do-projeto" class="anchor" aria-hidden="true" href="#-objetivo-do-projeto"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji> Objetivo do Projeto</h2>

<p dir="auto"> Conhecer os principais conceitos de mapeamento objeto relacional (ORM) usando o <strong>Spring Data JPA</strong>. Para isso, uma <strong>API RESTful</strong> foi desenvolvida com ênfase na modelagem de suas entidades, no domínio de uma academia de ginástica.</p>


<h2 dir="auto"><a id="user-content--pré-requistos" class="anchor" aria-hidden="true" href="#-pré-requistos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>
<g-emoji class="g-emoji" alias="stop_sign" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6d1.png">🛑</g-emoji> Pré-requistos
</h2>

<ul class="contains-task-list">
  <li class="task-list-item">
    <p dir="auto"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""> Fundamentos do Spring Boot</p>
  </li>
  <li class="task-list-item">
    <p dir="auto"><input type="checkbox" id="" disabled="" class="task-list-item-checkbox" checked=""> Noções de SQL</p>
  </li>
</ul>

<h2 dir="auto"><a id="user-content---guia-" class="anchor" aria-hidden="true" href="#--guia-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a> <g-emoji class="g-emoji" alias="vertical_traffic_light" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6a6.png">🚦</g-emoji> Guia </h2>

<ol dir="auto">
    <li> Apresentação do Projeto Base </li>
    <li> Configuração do banco de dados (SGBD <em>PostgreSQL</em>)</li>
    <li> Aplicando as <em>annotations</em></li>
    <li> Execução do fluxo back-end: <em>Controller - Service - Repository</em></li>
    <li> Validação - <em>Hibernate Validator</em> </li>
    <li> Consultas Avançadas - <em>Derived Query - Native Query</em></li>
</ol>

<h2 dir="auto"><a id="user-content--tecnologias-utilizadas" class="anchor" aria-hidden="true" href="#-tecnologias-utilizadas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="hammer_and_wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6e0.png">🛠</g-emoji> Tecnologias Utilizadas</h2>


<ul dir="auto">
    <li>IDE IntelliJ</li>
    <li>Java 11</li>
    <li>Maven</li>
    <li><strong>Spring Web</strong></li>
    <li><strong>Spring Data JPA</strong></li>
    <li><strong>PostgreSQL Driver</strong></li>
    <li><strong>Hibernate Validator</strong></li>
    <li>Lombok</li>
    <li>Postman</li>
</ul>

<h2 dir="auto"><a id="user-content-anotações-de-mapeamento-" class="anchor" aria-hidden="true" href="#anotações-de-mapeamento-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><a href="https://strn.com.br/artigos/2018/12/11/todas-as-anota%C3%A7%C3%B5es-do-jpa-anota%C3%A7%C3%B5es-de-mapeamento/" rel="nofollow">
Anotações de Mapeamento </a></h2>

<p dir="auto"><strong>@Entity</strong>
Usada para especificar que a classe anotada atualmente representa um tipo de entidade.</p>

<p dir="auto"><strong>@Table</strong>
Usada para especificar a tabela principal da entidade atualmente anotada.</p>

<p dir="auto"><strong>@Id</strong>
Especifica o identificador da entidade. Uma entidade deve sempre ter um atributo identificado.</p>

<p dir="auto"><strong>@GeneratedValue</strong>
Especifica que o valor do identificador de entidade é gerado automaticamente.</p>

<p dir="auto"><strong>@Column</strong>
Usada para especificar o mapeamento entre um atributo de entidade básico e a coluna da tabela de banco de dados.</p>

<p dir="auto"><strong>@JoinColumn</strong>
Usada para especificar a coluna FOREIGN KEY. Indica que a entidade é a responsável pelo relacionamento.</p>

<p dir="auto"><strong>@OneToMany</strong>
Usada para especificar um relacionamento de banco de dados um-para-muitos.</p>

<p dir="auto"><strong>@OneToOne</strong>
Usada para especificar um relacionamento de banco de dados um-para-um.</p>

<p dir="auto"><strong>@ManyToOne</strong>
Usada para especificar um relacionamento de banco de dados muitos-para-um.</p>

<p dir="auto"><strong>cascade</strong>
Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho.</p>

<p dir="auto"><strong>mappedBy</strong>
Indica qual é o lado inverso ou não dominante da relação.</p>

<h2 dir="auto"><a id="user-content--links-úteis" class="anchor" aria-hidden="true" href="#-links-úteis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="link" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f517.png">🔗</g-emoji> Links Úteis</h2>


<ul dir="auto">
    <li><a href="https://start.spring.io/#!type=maven-project&amp;language=java&amp;platformVersion=2.6.1&amp;packaging=jar&amp;jvmVersion=11&amp;groupId=me.dio.academia&amp;artifactId=academia-digital&amp;name=academia-digital&amp;description=Tutorial%20API%20RESTful%20modelando%20sistema%20de%20academia%20de%20gin%C3%A1stica&amp;packageName=me.dio.academia.digital&amp;dependencies=web,data-jpa,postgresql,validation,lombok" rel="nofollow">Spring Initializr</a></li>
    <li><a href="https://docs.spring.io/spring-boot/docs/2.0.x/reference/html/common-application-properties.html" rel="nofollow">Common application properties</a></li>
    <li><a href="https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.repositories" rel="nofollow">Spring Data JPA - Reference Documentation</a></li>
    <li><a href="https://docs.jboss.org/hibernate/stable/validator/reference/en-US/html_single/#validator-gettingstarted" rel="nofollow">Validation Reference Implementation: Reference Guide</a></li>
</ul>


<h2 dir="auto"><a id="user-content---contribuindo-" class="anchor" aria-hidden="true" href="#--contribuindo-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a> <g-emoji class="g-emoji" alias="handshake" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f91d.png">🤝</g-emoji> Contribuindo </h2>


<p dir="auto">Este repositório foi criado para fins de estudo, então contribua com ele. Se te ajudei de alguma forma, ficarei feliz em
saber. E caso você conheça alguém que se identidique com o conteúdo, não deixe de compatilhar.</p>




<p dir="auto"> Projeto desenvolvido utilizando a ajuda e os conhecimentos da Especialista: 
<a href="https://github.com/cami-la" title="cami-la" rel="nofollow">cami-la <g-emoji class="g-emoji" alias="hearts" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2665.png">♥</g-emoji> </a></p>
  


