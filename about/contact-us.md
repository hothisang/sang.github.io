# Please contact with us: 

# Testing Guide

This section provides comprehensive testing documentation for QDrant Loader, covering unit testing, integration testing, and quality assurance practices.

## 🎯 Testing Overview

QDrant Loader follows a comprehensive testing strategy to ensure reliability, performance, and maintainability:

### 🧪 Testing Philosophy

1. **Test-Driven Development** - Write tests before implementing features
2. **Comprehensive Coverage** - Aim for 85%+ test coverage
3. **Fast Feedback** - Quick unit tests for rapid development
4. **Real-World Testing** - Integration tests with actual services
5. **Performance Validation** - Regular performance benchmarking

### 📚 Testing Categories

- **Unit Testing** - Testing individual components in isolation
- **Integration Testing** - Testing component interactions and end-to-end workflows
- **Quality Assurance** - Code quality, review processes, and standards

## 🚀 Quick Start

### Test Environment Setup

```bash
# Clone the repository
cd qdrant-loader

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate

# Install packages in editable mode (workspace layout)
pip install -e packages/qdrant-loader
# Optional: MCP server if testing integration
pip install -e packages/qdrant-loader-mcp-server

# Install test tools
pip install pytest pytest-asyncio pytest-cov pytest-mock requests-mock responses

# Run all tests (verbose)
pytest -v

# Run with coverage per package (HTML reports under respective directories)
# Test qdrant-loader package


# Test website (from project root)
cd ../..
```
