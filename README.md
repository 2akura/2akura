```rs
//hana.desu


#[derive(Debug)]

struct TechStack {
    languages: Vec<&'static str>,
    major: String,
    databases: Vec<&'static str>,
    datalake: &'static str,
    related coursework: (&'static str, String)
}
fn main() {

    let tech_stack = TechStack {
        languages: vec!["Rust", "Python", "html", "css", "js", "C"],
        major: String::from ("Networking"),
        databases: vec ! [ "PostgreSQL" , "Cassandra" ],
        datalake: "Snowflake",
        related coursework: ( System Design, Algorithm Analyst)
    };
    
    println!("Tech Stack: {:#?}", tech_stack);
}

//我们相遇的那天。。。。。。。。
