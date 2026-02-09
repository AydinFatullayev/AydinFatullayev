import java.util.List;

public class AboutMe {
    public static class Person {
        private String name;
        private String surname;

        public String getName() { return name; }

        public void setName(String name) { this.name = name; }

        public String getSurname() { return surname; }

        public void setSurname(String surname) { this.surname = surname; }
    }

    public static class Knowledge {
        private List<String> languages;
        private List<String> dataBase;
        private List<String> noSQL;
        private List<String> frameworks;
        private List<String> tests;
        private List<String> devOps;
        private List<String> servers;
        private List<String> design;
        private List<String> others;
        

        public List<String> getLanguages() { return languages; }

        public void setLanguages(List<String> languages) { this.languages = languages; }

        public List<String> getDataBase() { return dataBase; }

        public void setDataBase(List<String> dataBase) { this.dataBase = dataBase; }

        public List<String> getNoSQL() { return noSQL; }

        public void setNoSQL(List<String> noSQL) { this.noSQL = noSQL; }

        public List<String> getFrameworks() { return frameworks; }

        public void setFrameworks(List<String> frameworks) { this.frameworks = frameworks; }

        public List<String> getTests() { return tests; }

        public void setTests(List<String> tests) { this.tests = tests; }
        
        public List<String> getDevOps() { return devOps; }

        public void setDevOps(List<String> devOps) { this.devOps = devOps; }

        public List<String> getServers() { return servers; }

        public void setServers(List<String> servers) { this.servers = servers; }

        public List<String> getDesign() { return design; }

        public void setDesign(List<String> design) { this.design = design; }

        public List<String> getOthers() { return others; }

        public void setOthers(List<String> others) { this.others = others; }
        
    }

    public static void main(String[] args) {
        Person person = new Person();
        Knowledge knowledge = new Knowledge();

        person.setName("Aydin");
        person.setSurname("Fatullayev");

        knowledge.setLanguages(List.of("Python", "Java"));
        knowledge.setDataBase(List.of("PostgreSQL", "MySQL", "OracleSQL", "JDBC", "Hibernate ORM"));
        knowledge.setNoSQL(List.of("MongoDB", "Redis"));
        knowledge.setFrameworks(List.of("Spring MVC", "Spring REST", "Spring Security", "Spring Boot", "Spring Data"));
        knowledge.setTests(List.of("JUnit"));
        knowledge.setDevOps(List.of("Docker", "Git"));
        knowledge.setServers(List.of("Apache", "Tomcat"));
        knowledge.setDesign(List.of("JSP", "XAML", "XML", "HTML", "CSS"));
        knowledge.setOthers(List.of("Linux", "Jira", "Postman", "KALI", "AOP", "IOC&DI", "Maven", "Gradle", "Flyway", "Liquibase"));

    }
}
