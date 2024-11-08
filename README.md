<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AccountingPro Suite - Professional Accounting Toolkits</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="text-xl font-bold text-indigo-600">AccountingPro Suite</div>
                </div>
                <div class="flex items-center space-x-8">
                    <a href="#" class="text-gray-700 hover:text-indigo-600">Home</a>
                    <div class="relative group">
                        <button class="text-gray-700 hover:text-indigo-600">Toolkits ▾</button>
                        <div class="absolute left-0 mt-2 w-48 rounded-md shadow-lg bg-white hidden group-hover:block">
                            <div class="py-1">
                                <a href="#audit" class="block px-4 py-2 text-sm text-gray-700 hover:bg-indigo-50">Audit Tools</a>
                                <a href="#analysis" class="block px-4 py-2 text-sm text-gray-700 hover:bg-indigo-50">Financial Analysis</a>
                                <a href="#tax" class="block px-4 py-2 text-sm text-gray-700 hover:bg-indigo-50">Tax Management</a>
                                <a href="#compliance" class="block px-4 py-2 text-sm text-gray-700 hover:bg-indigo-50">Compliance</a>
                            </div>
                        </div>
                    </div>
                    <a href="#" class="text-gray-700 hover:text-indigo-600">Pricing</a>
                    <a href="#" class="text-gray-700 hover:text-indigo-600">Support</a>
                    <a href="#" class="bg-indigo-600 text-white px-4 py-2 rounded-md hover:bg-indigo-700 transition-colors">
                        Get Started
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="bg-indigo-700 text-white pt-16">
        <div class="max-w-7xl mx-auto px-4 py-24">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div>
                    <h1 class="text-4xl md:text-5xl font-bold mb-6">
                        Complete Accounting Software Suite
                    </h1>
                    <p class="text-xl mb-8 text-indigo-100">
                        One platform, multiple toolkits. Everything you need for modern accounting, 
                        audit, tax, and compliance work.
                    </p>
                    <div class="space-x-4">
                        <a href="#toolkits" class="bg-white text-indigo-600 px-6 py-3 rounded-md font-medium hover:bg-gray-100 transition-colors inline-block">
                            Explore Toolkits
                        </a>
                        <a href="#" class="border border-white text-white px-6 py-3 rounded-md font-medium hover:bg-indigo-600 transition-colors inline-block">
                            Watch Demo
                        </a>
                    </div>
                </div>
                <div class="hidden md:block">
                    <img src="/api/placeholder/600/400" alt="AccountingPro Dashboard" class="rounded-lg shadow-xl">
                </div>
            </div>
        </div>
    </div>

    <!-- Toolkits Overview Section -->
    <div id="toolkits" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Professional Accounting Toolkits</h2>
            
            <!-- Audit Toolkit -->
            <div id="audit" class="mb-16">
                <div class="border-l-4 border-indigo-600 pl-4 mb-8">
                    <h3 class="text-2xl font-bold text-gray-800">Audit Toolkit</h3>
                    <p class="text-gray-600">Comprehensive tools for audit planning, execution, and documentation</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Transaction Vouching</h4>
                        <p class="text-gray-600 mb-4">Automated matching and verification of transactions with supporting documents</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Sampling Tool</h4>
                        <p class="text-gray-600 mb-4">Statistical and judgmental sampling for audit testing</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Risk Assessment</h4>
                        <p class="text-gray-600 mb-4">Systematic evaluation of audit risks and controls</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                </div>
            </div>

            <!-- Financial Analysis Toolkit -->
            <div id="analysis" class="mb-16">
                <div class="border-l-4 border-indigo-600 pl-4 mb-8">
                    <h3 class="text-2xl font-bold text-gray-800">Financial Analysis Toolkit</h3>
                    <p class="text-gray-600">Tools for comprehensive financial analysis and reporting</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Ratio Analysis</h4>
                        <p class="text-gray-600 mb-4">Calculate and interpret key financial ratios</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Trend Analysis</h4>
                        <p class="text-gray-600 mb-4">Historical trend analysis and forecasting</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Custom Reports</h4>
                        <p class="text-gray-600 mb-4">Generate customized financial reports</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                </div>
            </div>

            <!-- Tax Management Toolkit -->
            <div id="tax" class="mb-16">
                <div class="border-l-4 border-indigo-600 pl-4 mb-8">
                    <h3 class="text-2xl font-bold text-gray-800">Tax Management Toolkit</h3>
                    <p class="text-gray-600">Streamline tax calculations and compliance</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Tax Calculator</h4>
                        <p class="text-gray-600 mb-4">Automated tax calculations and estimations</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Tax Planning</h4>
                        <p class="text-gray-600 mb-4">Strategic tax planning and optimization tools</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Filing Assistant</h4>
                        <p class="text-gray-600 mb-4">Streamlined tax return preparation and filing</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                </div>
            </div>

            <!-- Compliance Toolkit -->
            <div id="compliance" class="mb-16">
                <div class="border-l-4 border-indigo-600 pl-4 mb-8">
                    <h3 class="text-2xl font-bold text-gray-800">Compliance Toolkit</h3>
                    <p class="text-gray-600">Ensure regulatory compliance and reporting requirements</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Compliance Checker</h4>
                        <p class="text-gray-600 mb-4">Automated compliance verification and reporting</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Regulatory Updates</h4>
                        <p class="text-gray-600 mb-4">Stay current with regulatory requirements</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md border border-gray-200 hover:border-indigo-500 transition-colors">
                        <h4 class="text-lg font-semibold mb-3">Document Manager</h4>
                        <p class="text-gray-600 mb-4">Organize and track compliance documentation</p>
                        <a href="#" class="text-indigo-600 hover:text-indigo-800">Learn more →</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- CTA Section -->
    <div class="bg-indigo-700 text-white py-16">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8">Ready to transform your accounting workflow?</h2>
            <p class="text-xl text-indigo-100 mb-8">Start your free trial and explore all our professional toolkits</p>
            <div class="space-x-4">
                <a href="#" class="bg-white text-indigo-600 px-8 py-4 rounded-md font-medium hover:bg-gray-100 transition-colors inline-block">
                    Start Free Trial
                </a>
                <a href="#" class="border border-white text-white px-8 py-4 rounded-md font-medium hover:bg-indigo-600 transition-colors inline-block">
                    Schedule Demo
                </a>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300">
        <div class="max-w-7xl mx-auto px-4 py-12">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-white text-lg font-semibold mb-4">AccountingPro Suite</h3>
                    <p>Professional accounting tools for modern businesses</p>
                </div>
                <div>
                    <h4 class="text-white text-lg font-semibold mb-4">Toolkits</h4>
                    <ul class="space-y-2">
                        <li><a href="#audit" class="hover:text-white">Audit Tools</a></li>
                        <li><a href="#analysis" class="hover:text-white">Financial Analysis</a></li>
                        <li><a href="#tax" class="hover:text-white">Tax Management</a></li>
                        <li><a href="#compliance" class="hover:text-white">Compliance</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white text-lg font-semibold mb-4">Resources</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-white">Documentation</a></li>
                        <li><a href="#" class="hover:text-white">API Reference</a></li>
                        <li><a href="#" class="hover:text-white">User Guides</a></li>
                        <li><a href="#" class="hover:text-white">Blog</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white text-lg font-semibold mb-4">Company</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-white">About Us</a></li>
                        <li><a href="#" class="hover:text-white">Contact</a></li>
                        <li><a href="#" class="hover:text-white">Privacy Policy</a></li>
                        <li><a href="#" class="hover:text-white">Terms of Service</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p>© 2024 AccountingPro Suite. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Feature Highlights Section -->
    <div class="bg-gray-50 py-24">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-16">Why Choose AccountingPro Suite?</h2>
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Integrated Suite</h3>
                    <p class="text-gray-600">All your accounting tools in one unified platform</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Bank-Grade Security</h3>
                    <p class="text-gray-600">Enterprise-level security for your financial data</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Automated Workflows</h3>
                    <p class="text-gray-600">Streamline repetitive tasks and processes</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Cloud-Based</h3>
                    <p class="text-gray-600">Access your tools anywhere, anytime</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
