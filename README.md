# Hi, I'm Emman Lazo 👋

**System Programmer | C#/.NET Developer | CAD Automation Specialist**

I build practical automation solutions that connect engineering workflows with software. My main focus is developing C# applications and APIs for **AutoCAD, SolidWorks, and CADMATIC**, turning drawing data into accurate, repeatable, and less manual processes.

I enjoy solving geometry-heavy problems, debugging complex workflows, and improving working systems through careful, incremental changes. I value output accuracy, readable code, and solutions that can be tested and maintained in real engineering environments.

## 👨‍💻 About Me

- 💼 Working as a **System Programmer**
- 📍 Based in Metro Manila, Philippines
- ⚙️ Specialized in **CAD automation and engineering software integration**
- 🧩 Experienced in processing lines, circles, blocks, dimensions, annotations, and coordinate data
- 🔄 Building end-to-end workflows between **AutoCAD and SolidWorks**
- 🛠️ Comfortable with debugging, refactoring, API integration, and geometry-based logic
- 📚 Continuously improving my software architecture, coding consistency, and documentation practices
- 🤝 I enjoy collaborating with engineers, programmers, and international team members

## 🚀 What I Work On

### AutoCAD to SolidWorks Automation

I develop automation pipelines that extract and process engineering data from AutoCAD drawings, then use the SolidWorks API to generate accurate 3D parts and assemblies.

My work includes:

- Extracting block references and their nested entities
- Reading lines, circles, dimensions, text, and annotations
- Segregating drawing data based on engineering rules
- Building connected chains from line geometry
- Detecting horizontal, vertical, and angled directions
- Matching angular dimensions with the correct geometry
- Handling front, rear, left, and right view orientations
- Creating fully defined SolidWorks sketches
- Applying dimensions, constraints, fillets, and bevels
- Generating stubs and headers from prepared drawing data
- Connecting generated components using processed reference information
- Assigning part names and custom properties automatically
- Validating outputs to prevent small coordinate or angle errors

### Application and API Development

I also build supporting tools and applications for engineering automation, including:

- C# and .NET desktop applications
- Windows Forms tools
- AutoCAD .NET API integrations
- SolidWorks API integrations
- Engineering data preparation and validation
- File and naming automation
- SQL-backed application workflows
- Reusable models and processing utilities

## 🧰 Tech Stack

### Languages and Frameworks

- C#
- .NET
- Windows Forms
- LINQ
- SQL

### Engineering and CAD

- AutoCAD .NET API
- SolidWorks API
- CADMATIC
- Geometry processing
- Parametric sketch automation
- Engineering drawing interpretation

### Development Tools

- Visual Studio
- Visual Studio Code
- SQL Server
- Git and GitHub
- Docker
- Android Studio

## 🧠 My Coding Approach

### Accuracy First

In CAD automation, a small decimal difference can create an incorrect SolidWorks result. I carefully validate coordinates, angles, entity relationships, and dimensions before generating the final model.

### Preserve Working Logic

I prefer targeted and incremental improvements instead of rewriting a working system without a clear reason. I keep stable checkpoints and test each modification before moving to the next one.

### Prepare Data Before Creation

I separate data extraction and preparation from model creation. This makes the workflow easier to debug and helps ensure that SolidWorks receives complete and validated data.

```csharp
List<PreparedStubData> preparedStubs = PrepareStubData(blocks);

foreach (PreparedStubData stub in preparedStubs)
{
    ValidateStubData(stub);
    CreateSolidWorksStub(stub);
}
```

### Handle Real Drawing Edge Cases

Engineering drawings are not always perfectly consistent. I design logic that considers cases such as:

- Extra lines inside block references
- Missing or duplicated entities
- Single-line and multi-line chains
- Horizontal, vertical, and angled geometry
- Different drawing view orientations
- Floating-point precision differences
- Incorrect entity matching
- Incomplete sketch definitions

### Debug with Meaningful Data

I use structured debug output to verify processed values before they reach the CAD creation stage.

```text
Block: A-A
Chain: 1
Lines: 2
Direction: Angled
Angle: 20
Status: Prepared and validated
```

## 🌟 Strengths

- Strong problem-solving skills for geometry-based automation
- Fast learner who adapts to unfamiliar APIs and systems
- Practical experience integrating multiple engineering applications
- Detail-oriented when validating technical outputs
- Comfortable tracing complex data through multiple processing stages
- Able to translate drawing requirements into program logic
- Collaborative and responsive to technical feedback
- Focused on building useful solutions, not just writing code

## 📈 Currently Improving

- Software architecture and design patterns
- Unit and integration testing for CAD workflows
- Consistent naming and coding standards
- Reusable service-based application structure
- Performance optimization for large drawing datasets
- Technical documentation and maintainability
- Broader DevOps and deployment practices

## 🏗️ Featured Project

### Automated Stub and Header Generation

An AutoCAD-to-SolidWorks automation project that converts drawing information into prepared engineering data and generates SolidWorks components programmatically.

**Core workflow:**

1. Read AutoCAD blocks and entities
2. Segregate relevant drawing information
3. Build and validate connected line chains
4. Determine direction, angle, and view orientation
5. Match dimensions and annotations
6. Prepare normalized stub and header data
7. Generate fully defined SolidWorks sketches and features
8. Apply fillets, bevels, names, and custom properties
9. Position and connect the generated components
10. Validate the final engineering output

**Key goal:** Reduce repetitive manual modeling while maintaining the precision required for engineering production.

## 🤝 Let's Connect

I am interested in projects involving:

- CAD and engineering automation
- C#/.NET development
- AutoCAD and SolidWorks API integration
- Geometry and drawing-data processing
- Desktop engineering tools
- Workflow and process automation

Feel free to explore my repositories and connect with me for collaboration, knowledge sharing, or engineering automation opportunities.

---

> I believe good automation should be accurate, understandable, testable, and useful to the people who rely on it.
