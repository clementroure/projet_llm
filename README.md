
# Description
This is a tool that leverages the power of LangChain and LLM technologies. It's designed to automatically generate personalized cover letters by analyzing job postings and the user's CV.

## Initial Setup
First, create a dedicated virtual environment to manage dependencies:
```bash
python3 -m venv env
```

Next, activate the virtual environment:
```bash
source env/bin/activate
```

Finally, install all the required dependencies:
```bash
pip install -r requirements.txt
```

Finally, replace the job url and the ./cv.pdf file

### Required Parameters
- `--link_to_job`: The URL of the job posting you're applying to.
- `--cv_pdf_path`: The file path to your CV, which must be in PDF format.
- `--openai_key`: Your OpenAI API key for accessing GPT models.

### Usage Example
Run QuickCoverLetter with the following command:
```bash
bash create_cover_letter \
  --job_url="https://www.linkedin.com/jobs/view/3778594855" \
  --cv_file_path="./cv.pdf" \
  --openai_api_key="<api_key>"
```

### Output

Dear Sir or Madam,

I am writing to express my interest in the Blockchain Developer position at Open Systems Technologies. As an experienced Blockchain Full-Stack Engineer with a background in Fintech, I am confident that I possess the skills and experience necessary to excel in this role.

Having read the job posting, I was immediately drawn to the opportunity to work with cutting-edge blockchain technology in the heart of New York City. With my strong academic background in engineering and courses specifically focused on smart contracts, blockchain architecture, and advanced web development, I am well-equipped to contribute to the development of secure and scalable blockchain applications and protocols.

In my current role at Every Finance, I have successfully developed a Node.js backend to monitor wallet balances and estimated USD values across multiple EVM blockchains. I have also devised efficient algorithms for valuing LP tokens from popular DEXs and integrated a DeFi aggregator to optimize trading costs. My experience in leading DevOps strategies and enhancing cybersecurity defenses also aligns with the responsibilities listed in the job description.

Additionally, during my time at PyratzLabs, I built an On-chain EVM agent-based DeFi simulator that runs 300% faster than the official TokenSpice Python library. I also have experience working with a variety of programming languages and technologies, including Solidity, Rust, TypeScript, Node.js, Nest, GraphQL, and more.

Furthermore, I am continually staying up to date with the latest advancements in blockchain technology, protocols, and industry trends. My strong understanding of blockchain architecture, consensus mechanisms, and cryptographic techniques, coupled with my proficiency in security best practices, make me a valuable asset to any blockchain development team.

I am eager to bring my skills and passion for blockchain technology to Open Systems Technologies and contribute to its success. Thank you for considering my application. I look forward to the opportunity to discuss my qualifications further.

Sincerely,
Clément Roure