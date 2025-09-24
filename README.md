# Create project documentation
@"
# SkillMentor - Peer Learning Platform

## Project Structure
- \`backend/\` - Spring Boot REST API
- \`frontend/\` - Angular Web Application
- \`docs/\` - Project documentation

## Quick Start

### Backend Setup:
\`\`\`bash
cd backend
# Copy and configure application properties
cp src/main/resources/application-template.properties src/main/resources/application.properties
# Start the application
mvn spring-boot:run
\`\`\`

### Frontend Setup:
\`\`\`bash
cd frontend
npm install
ng serve
\`\`\`

## Access Points
- Frontend: http://localhost:4200
- Backend API: http://localhost:8080
"@ | Out-File -FilePath "README.md" -Encoding UTF8
