```rs
//hana.desu


#[derive(Debug)]
struct TechStack {
    languages: Vec<&'static str>,
    major: String,
    databases: Vec<&'static str>,
    datalake: &'static str,
}
fn main() {

    let tech_stack = TechStack {
        languages: vec!["Rust", "Haskell", "Python", "html", "css", "js", "C"],
        major: String::from ("Networking"),
        databases: vec ! [ "PostgreSQL" , "Cassandra" ],
        datalake: "Snowflake",
    };
    
    println!("Tech Stack: {:#?}", tech_stack);
}

//我们相遇的那天。。。。。。。。
