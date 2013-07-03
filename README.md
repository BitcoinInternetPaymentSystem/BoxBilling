Copyright (C) 2011 by Kris

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
	Bitcoin payments via BIPS for BoxBilling.

Version 0.1
	
System Requirements:
	BIPS API, Merchant Secret
	BoxBilling v3.6.11
	PHP 5+
	Curl PHP Extension
  
Configuration Instructions:
	1. Upload files to your BoxBilling installation.
	2. Go to your BoxBilling configuration. Payment Gateways -> New payment gateway -> "BIPS" click [Install]
	3. In BIPS Callback URL (https://bips.me/merchant) Enter the link to your callback of BIPS BoxBilling Payment Module, located under settings of module.
	4. Enter a strong Secret in Merchant SECRET.
	5. In module settings "API" <- set your BIPS API Key, which can be generate under API Keys, Invoice.
	6. In module settings "Secret" <- Enter your BIPS Merchant Secret.