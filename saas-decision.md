## **Current Reputable OAuth2 Providers**

OAuth2 is an open standard protocol for authorization widely used in the software industry. While there are many SaaS providers that support OAuth2, here are some of the reputable ones that are commonly used:

1. Google OAuth2: Google provides OAuth2 as a standard mechanism for authorization across all its services. It is widely used in web and mobile applications that integrate with Google APIs.
2. Microsoft Azure Active Directory: Microsoft Azure provides a comprehensive set of tools and services for managing authentication and authorization in cloud-based applications. Azure Active Directory supports OAuth2 and is widely used in enterprise applications.
3. Amazon Cognito: Amazon Cognito is a fully managed user authentication and authorization service that supports OAuth2. It is widely used in mobile and web applications that need secure access to AWS resources.
4. Auth0: Auth0 is a cloud-based authentication and authorization platform that supports OAuth2 and other protocols such as SAML, OpenID Connect, and LDAP. It is widely used in enterprise applications and has a large community of developers.
5. Okta: Okta is a cloud-based identity management platform that supports OAuth2 and other protocols such as SAML, OpenID Connect, and LDAP. It is widely used in enterprise applications and provides a range of features for managing user identity and access.

## **Features**

### **SAML2 & OpenID Connect**

All of the OAuth2 SaaS providers mentioned above support integration with SAML2 and OpenID Connect protocols, in addition to OAuth2. Here is a brief overview of how each provider supports these protocols:

1. Google OAuth2: Google provides support for OpenID Connect and SAML2 in addition to OAuth2. These protocols are used for authentication and authorization of users for accessing Google APIs.
2. Microsoft Azure Active Directory: Azure Active Directory supports OpenID Connect and SAML2 protocols in addition to OAuth2. These protocols are used for authentication and authorization of users for accessing cloud-based applications and services.
3. Amazon Cognito: Amazon Cognito supports OpenID Connect and SAML2 protocols in addition to OAuth2. These protocols are used for authentication and authorization of users for accessing mobile and web applications that need secure access to AWS resources.
4. Auth0: Auth0 supports OAuth2, OpenID Connect, and SAML2 protocols, as well as other protocols such as LDAP. These protocols are used for authentication and authorization of users for accessing cloud-based applications and services.
5. Okta: Okta supports OAuth2, OpenID Connect, and SAML2 protocols, as well as other protocols such as LDAP. These protocols are used for authentication and authorization of users for accessing cloud-based applications and services.

### **MFA**

All of the OAuth2 SaaS providers mentioned earlier provide support for Multi-Factor Authentication (MFA) as an additional layer of security to protect user accounts. Here's a brief overview of how each provider supports MFA:

1. Google OAuth2: Google provides support for MFA through the use of its Google Authenticator app or other third-party authentication apps that support the Time-based One-Time Password (TOTP) protocol. Users can set up MFA for their Google account through their account settings.
2. Microsoft Azure Active Directory: Azure Active Directory provides support for MFA through the use of the Microsoft Authenticator app or other third-party authentication apps that support TOTP. Users can set up MFA for their Azure AD account through their account settings.
3. Amazon Cognito: Amazon Cognito provides support for MFA through the use of TOTP-based authentication apps or SMS-based verification codes. Users can set up MFA for their Cognito user pool through the AWS Management Console or through the Cognito API.
4. Auth0: Auth0 provides support for MFA through the use of the Auth0 Guardian app, SMS-based verification codes, or email-based verification links. Users can set up MFA for their Auth0 account through their account settings.
5. Okta: Okta provides support for MFA through the use of the Okta Verify app, SMS-based verification codes, or email-based verification links. Users can set up MFA for their Okta account through their account settings.

### **Password Reset**

#### **Question & Answer**

All of the OAuth2 SaaS providers mentioned earlier support some form of password reset functionality, including the use of security questions and answers. Here's a brief overview of how each provider supports this functionality:

1. Google OAuth2: Google provides a password reset process that involves answering security questions, using a backup email address or phone number, or providing other identifying information to verify the user's identity.
2. Microsoft Azure Active Directory: Azure Active Directory provides a password reset process that can be customized to include security questions and answers, two-factor authentication, and other forms of identity verification.
3. Amazon Cognito: Amazon Cognito provides a password reset process that can include security questions and answers, as well as SMS-based verification codes or email-based verification links.
4. Auth0: Auth0 provides a customizable password reset process that can include security questions and answers, as well as other forms of identity verification such as SMS-based codes or biometric authentication.
5. Okta: Okta provides a password reset process that can include security questions and answers, as well as other forms of identity verification such as SMS-based codes, biometric authentication, or email-based verification links.

#### **Email**

All of the OAuth2 SaaS providers mentioned earlier provide support for resetting passwords via email links. This is a common password reset method that involves sending a unique link to the user's email address that, when clicked, allows the user to reset their password. Here's a brief overview of how each provider supports this functionality:

1. Google OAuth2: Google provides a password reset process that includes sending an email with a unique link to the user's recovery email address. Clicking the link takes the user to a page where they can create a new password.
2. Microsoft Azure Active Directory: Azure Active Directory provides a password reset process that includes sending an email with a unique link to the user's registered email address. Clicking the link takes the user to a page where they can create a new password.
3. Amazon Cognito: Amazon Cognito provides a password reset process that includes sending an email with a unique link to the user's registered email address. Clicking the link takes the user to a page where they can create a new password.
4. Auth0: Auth0 provides a password reset process that includes sending an email with a unique link to the user's registered email address. Clicking the link takes the user to a page where they can create a new password.
5. Okta: Okta provides a password reset process that includes sending an email with a unique link to the user's registered email address. Clicking the link takes the user to a page where they can create a new password.

Overall, each provider offers similar functionality for resetting passwords via email links. The specific implementation may vary slightly, but the basic process involves sending an email with a unique link that allows the user to reset their password securely.

### **SMS-Based Verification**

All of the OAuth2 SaaS providers mentioned earlier provide support for SMS-based verification codes as a form of Multi-Factor Authentication (MFA) or as part of the password reset process. Here's a brief overview of how each provider supports SMS-based verification codes:

1. Google OAuth2: Google provides support for SMS-based verification codes as part of its MFA process. Users can set up SMS-based verification codes for their Google account through their account settings.
2. Microsoft Azure Active Directory: Azure Active Directory provides support for SMS-based verification codes as part of its MFA process. Users can set up SMS-based verification codes for their Azure AD account through their account settings.
3. Amazon Cognito: Amazon Cognito provides support for SMS-based verification codes as part of its MFA process. Users can set up SMS-based verification codes for their Cognito user pool through the AWS Management Console or through the Cognito API.
4. Auth0: Auth0 provides support for SMS-based verification codes as part of its MFA process or as part of the password reset process. Users can set up SMS-based verification codes for their Auth0 account through their account settings.
5. Okta: Okta provides support for SMS-based verification codes as part of its MFA process or as part of the password reset process. Users can set up SMS-based verification codes for their Okta account through their account settings.

### **Organization**

All of the OAuth2 SaaS providers mentioned earlier support handling organizations, either through built-in features or integrations with other services. Here's a brief overview of how each provider supports organizations:

1. Google OAuth2: Google provides support for organizations through its Google Cloud Identity platform, which offers features such as user and group management, single sign-on (SSO), and access control for Google Cloud Platform services and third-party applications.
2. Microsoft Azure Active Directory: Azure Active Directory provides comprehensive support for organizations, including features such as user and group management, SSO, access control for Microsoft services and third-party applications, and integration with other Microsoft services such as Azure DevOps and Dynamics 365.
3. Amazon Cognito: Amazon Cognito provides support for organizations through its user pool feature, which allows for user and group management, access control, and integration with third-party applications.
4. Auth0: Auth0 provides support for organizations through its tenant feature, which allows for user and group management, access control, SSO, and integration with third-party applications.
5. Okta: Okta provides comprehensive support for organizations, including features such as user and group management, SSO, access control for both cloud and on-premises applications, and integration with other services such as HR and IT management systems.

## **Cost** 

### **Pricing Structure**

The costs and pricing structures for the OAuth2 SaaS providers mentioned earlier vary depending on the specific services and features used. Here's a brief overview of the pricing models for each provider:

1. Google OAuth2: Google provides OAuth2 as part of its Google Cloud Platform, which offers a variety of services with different pricing models. Some of the services, such as Google Sign-In and Firebase Authentication, offer free usage up to a certain limit, with additional usage charged based on usage metrics such as number of users or API calls.
2. Microsoft Azure Active Directory: Azure Active Directory is offered as a standalone service or as part of the Azure cloud platform. The pricing for Azure AD varies based on the number of users and features used, with some features, such as MFA and self-service password reset, offered for free.
3. Amazon Cognito: Amazon Cognito offers a free tier for up to 50,000 monthly active users, with additional usage charged based on the number of users and usage metrics such as data storage and API calls.
4. Auth0: Auth0 offers a range of pricing plans based on the number of monthly active users and the features required. Some features, such as email and SMS-based authentication, are offered for free, while other features, such as MFA and custom branding, require a paid plan.
5. Okta: Okta offers a range of pricing plans based on the number of users and features required. Some features, such as MFA and API access management, are offered for free, while other features, such as advanced reporting and custom workflows, require a paid plan.

### **Pricing References**

Here are the URLs for the pricing pages for each OAuth2 SaaS provider mentioned earlier:

1. Google OAuth2: [https://cloud.google.com/pricing#authentication](https://cloud.google.com/pricing#authentication)
2. Microsoft Azure Active Directory: [https://azure.microsoft.com/en-us/pricing/details/active-directory/](https://azure.microsoft.com/en-us/pricing/details/active-directory/)
3. Amazon Cognito: [https://aws.amazon.com/cognito/pricing/](https://aws.amazon.com/cognito/pricing/)
4. Auth0: [https://auth0.com/pricing/](https://auth0.com/pricing/)
5. Okta: [https://www.okta.com/pricing/](https://www.okta.com/pricing/)

Note that the pricing pages for each provider may include additional details and options beyond what is mentioned in this response, so it's important to review each provider's pricing page carefully and reach out to the provider's sales team for any questions or clarifications.

## Summary

Here is the summary paper that includes the reputable OAuth2 SaaS providers, their pros and cons, and available features along with the cost reference URLs:

1. Google OAuth2:

Pros:

* Easy integration with other Google APIs
* High level of security and reliability
* Wide adoption and community support
* Free to use

Cons:

* Limited customization options
* Limited support for non-Google services

Available Features:

* OAuth2, OpenID Connect, and SAML2 support
* Password reset with security questions, backup email/phone, and identifying information
* MFA with Google Authenticator or other TOTP apps

Pricing URL: [https://cloud.google.com/pricing#authentication](https://cloud.google.com/pricing#authentication)

2. Microsoft Azure Active Directory:

Pros:

* Comprehensive set of authentication and authorization features
* Integration with Microsoft services and other third-party services
* Highly scalable and secure
* Active community and support resources

Cons:

* Complex setup and configuration process
* Requires a subscription to use some features

Available Features:

* OAuth2, OpenID Connect, and SAML2 support
* Password reset with security questions, two-factor authentication, and other forms of identity verification
* MFA with Microsoft Authenticator or other TOTP apps

Pricing URL: [https://azure.microsoft.com/en-us/pricing/details/active-directory/](https://azure.microsoft.com/en-us/pricing/details/active-directory/)

3. Amazon Cognito:

Pros:

* Easy integration with other AWS services
* High level of security and scalability
* Low cost for small to medium-scale applications
* Support for multiple authentication protocols

Cons:

* Limited customization options
* Limited support for non-AWS services
* Complexity increases as application scales

Available Features:

* OAuth2, OpenID Connect, and SAML2 support
* Password reset with security questions, SMS-based verification codes, or email-based verification links
* MFA with SMS-based verification codes or TOTP-based authentication apps

Pricing URL: [https://aws.amazon.com/cognito/pricing/](https://aws.amazon.com/cognito/pricing/)

4. Auth0:

Pros:

* Comprehensive set of authentication and authorization features
* High level of customization and flexibility
* Support for multiple authentication protocols
* Strong community and support resources

Cons:

* Higher cost compared to other providers
* Complexity increases as application scales

Available Features:

* OAuth2, OpenID Connect, and SAML2 support
* Password reset with security questions, SMS-based verification codes, or email-based verification links
* MFA with Auth0 Guardian app, SMS-based verification codes, or biometric authentication

Pricing URL: [https://auth0.com/pricing/](https://auth0.com/pricing/)

5. Okta:

Pros:

* Comprehensive set of authentication and authorization features
* Integration with multiple third-party services
* Strong focus on security and compliance
* High level of customization and scalability

Cons:

* Higher cost compared to other providers
* Complexity increases as application scales

Available Features:

* OAuth2, OpenID Connect, and SAML2 support
* Password reset with security questions, SMS-based verification codes, or email-based verification links
* MFA with Okta Verify app, SMS-based verification codes, or email-based verification links

Pricing URL: [https://www.okta.com/pricing/](https://www.okta.com/pricing/)

Overall, each OAuth2 SaaS provider has its own set of strengths and weaknesses, and the choice of provider will depend on the specific needs and requirements of the application. It's important to carefully evaluate each provider based on factors such as security, scalability, customization options, support, and cost before making a decision.

Here is a summary of the OAuth2 SaaS providers mentioned earlier, their pros and cons, available features, and cost reference URLs in a tabular form:

| OAuth2 SaaS Provider             | Pros                                                                                                                                                                                                 | Cons                                                                                                            | Available Features                                                               | Cost Reference URL                                                                                                                      |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Google OAuth2                    | Easy integration with Google APIs, high level of security and reliability, free to use                                                                                                               | Limited customization options, limited support for non-Google services                                          | OAuth2, OpenID Connect, SAML2                                                    | [https://cloud.google.com/pricing#authentication](https://cloud.google.com/pricing#authentication)                                         |
| Microsoft Azure Active Directory | Comprehensive set of authentication and authorization features, integration with Microsoft and third-party services, highly scalable and secure                                                      | Complex setup and configuration process, requires a subscription for some features                              | OAuth2, OpenID Connect, SAML2, MFA, password reset, self-service password reset  | [https://azure.microsoft.com/en-us/pricing/details/active-directory/](https://azure.microsoft.com/en-us/pricing/details/active-directory/) |
| Amazon Cognito                   | Easy integration with AWS services, high level of security and scalability, low cost for small to medium-scale applications                                                                          | Limited customization options, limited support for non-AWS services, complexity increases as application scales | OAuth2, OpenID Connect, SAML2, MFA, password reset, SMS-based verification codes | [https://aws.amazon.com/cognito/pricing/](https://aws.amazon.com/cognito/pricing/)                                                         |
| Auth0                            | Comprehensive set of authentication and authorization features, high level of customization and flexibility, support for multiple authentication protocols                                           | Higher cost compared to other providers, complexity increases as application scales                             | OAuth2, OpenID Connect, SAML2, MFA, password reset, SMS-based verification codes | [https://auth0.com/pricing/](https://auth0.com/pricing/)                                                                                   |
| Okta                             | Comprehensive set of authentication and authorization features, integration with multiple third-party services, strong focus on security and compliance, high level of customization and scalability | Higher cost compared to other providers, complexity increases as application scales                             | OAuth2, OpenID Connect, SAML2, MFA, password reset, SMS-based verification codes | [https://www.okta.com/pricing/](https://www.okta.com/pricing/)                                                                             |

## Configuration

### AWS Cognito

Here is the list of steps to set up AWS Cognito for the first time:

1. Create a user pool:
   - Navigate to the Cognito User Pools console and click "Create a user pool".
   - Fill in the required fields to configure the user pool settings, such as the pool name, sign-in options, and multi-factor authentication (MFA) settings.
   - Configure the user pool policies, such as the password policy and user attributes.
   - Create any necessary app clients for your application to use to interact with the user pool.

2. Add users to the user pool:
   - Navigate to the "Users and groups" tab in the Cognito User Pools console.
   - Click "Create user" to manually create a user, or import users from a CSV file.
   - Configure the user's attributes, such as their email address and password.

3. Configure sign-in options:
   - Choose the sign-in method(s) that you want to enable for your user pool, such as username/password, email/verification code, or third-party identity providers like Facebook or Google.
   - Configure any necessary identity providers using the "Federation" tab in the Cognito User Pools console.

4. Configure app integration:
   - Configure any app clients that you created in step 1 to interact with the user pool using OAuth2 or SAML2 integration.
   - Use the appropriate SDK or API to integrate your application with the user pool for user authentication and authorization.

#### OpenId Connect Integration

Configuring Amazon Cognito to allow Single Sign-On (SSO) with another app through OpenID Connect involves several steps, which include creating an OpenID Connect app client in Cognito, configuring the SSO settings, and integrating the app with the OpenID Connect provider. Here's an overview of the steps involved:

1. Create an OpenID Connect app client in Amazon Cognito: The first step is to create an app client in Cognito that will be used to authenticate users. This involves specifying the app client settings such as the client name, OAuth2.0 scopes, and redirect URIs.
2. Configure the SSO settings: Once the app client is created, the next step is to configure the SSO settings in Cognito. This involves setting up the SSO domain name, adding the app client to the SSO domain, and configuring the sign-in and sign-out URLs.
3. Integrate the app with the OpenID Connect provider: The next step is to integrate the app with the OpenID Connect provider. This involves obtaining the provider's metadata URL or metadata file, and configuring the OpenID Connect settings in Cognito such as the authorization endpoint, token endpoint, and user info endpoint.
4. Test the SSO integration: Finally, once the app client and SSO settings are configured, it's important to test the SSO integration to ensure that everything is working as expected. This involves logging in to the app using the Cognito app client and verifying that the user is able to authenticate and access the appropriate resources.

#### SAML2 Integration

Configuring Amazon Cognito to allow SAML2 integration involves several steps, which include setting up a SAML identity provider (IdP), configuring a user pool in Cognito, and mapping SAML attributes to user pool attributes. Here's an overview of the steps involved:

1. Set up a SAML IdP: The first step is to set up a SAML IdP that will be used to authenticate users. This can be done using a third-party IdP such as Okta or Microsoft Azure AD, or using an IdP that is hosted on-premises.
2. Configure a user pool in Amazon Cognito: Once the SAML IdP is set up, the next step is to create a user pool in Amazon Cognito. This involves defining the user pool settings, such as the user attributes that will be used to store user data and the MFA settings.
3. Configure the SAML identity provider in Cognito: The next step is to configure the SAML IdP in Amazon Cognito. This involves providing the IdP metadata URL or uploading the metadata file, as well as configuring the SAML assertion settings such as the audience and recipient URLs.
4. Map SAML attributes to user pool attributes: After configuring the SAML IdP in Cognito, the next step is to map the SAML attributes to user pool attributes. This involves defining how the SAML attributes will be mapped to user pool attributes such as username, email address, and custom attributes.
5. Test the SAML integration: Finally, once the SAML IdP and user pool are configured and the attribute mappings are defined, it's important to test the SAML integration to ensure that everything is working as expected. This involves logging in using a SAML identity provider and verifying that the user is able to authenticate and access the appropriate resources.

### Okta

Here is the list of steps to set up Okta for the first time:

1. Create an Okta organization:
   - Navigate to the Okta website and sign up for a new account.
   - Follow the prompts to configure your organization settings, such as your company name and primary administrator account.

2. Create an Okta application:
   - Navigate to the Okta Admin Console and click "Applications" from the top menu.
   - Click the "Add Application" button and select the application type that you want to create.
   - Fill in the required fields to configure the application settings, such as the application name, sign-on method, and redirect URIs.
   - Configure any necessary identity providers or user attributes for the application.

3. Add users to Okta:
   - Navigate to the Okta Admin Console and click "Directory" from the top menu.
   - Click "People" and then click "Add Person" to manually create a user, or import users from a CSV file.
   - Configure the user's attributes, such as their email address and password.

4. Configure app integration:
   - Use the appropriate SDK or API to integrate your application with Okta for user authentication and authorization.
   - Configure the SAML2 or OAuth2 settings for your application to interact with Okta, such as the client ID, client secret, and authorization scopes.

5. Test the integration:
   - Use the test user accounts and app credentials provided by Okta to test the integration between your application and Okta.
   - Verify that users can authenticate and access the appropriate resources and functionality within your application.

#### OpenId Connect Integration

Here is how to setup an application to SSO with Okta using OAuth2:

1. Set up an OAuth2 app in Okta:
   - Navigate to the Okta Admin Console and select "Applications" from the top menu.
   - Click the "Add Application" button and select "Create New App".
   - Choose "Web" as the platform and "OpenID Connect" as the sign-on method.
   - Fill in the required fields to create a new OAuth2 app in Okta.
   - Configure the OAuth2 settings for the app, including the client ID, client secret, redirect URIs, and authorization scopes.

2. Configure the application to use Okta for OAuth2 authentication:
   - In your application, configure the OAuth2 settings to use the Okta OAuth2 endpoints and authorization parameters.
   - When a user logs in to your application, redirect them to the Okta OAuth2 authorize URL.
   - After the user authenticates with Okta, Okta will redirect them back to your application with an authorization code.

3. Implement OAuth2-based authentication and authorization in your application:
   - Exchange the authorization code received from Okta for an access token and refresh token.
   - Use the access token to authenticate the user within your application.
   - Authorize the user to access the appropriate resources and functionality within your application.
   - Refresh the access token as needed using the refresh token.

#### SAML2 Integration

Here is how to setup an application to SSO with Okta using OAuth2:

1. Set up an OAuth2 app in Okta:
   - Navigate to the Okta Admin Console and select "Applications" from the top menu.
   - Click the "Add Application" button and select "Create New App".
   - Choose "Web" as the platform and "OpenID Connect" as the sign-on method.
   - Fill in the required fields to create a new OAuth2 app in Okta.
   - Configure the OAuth2 settings for the app, including the client ID, client secret, redirect URIs, and authorization scopes.

2. Configure the application to use Okta for OAuth2 authentication:
   - In your application, configure the OAuth2 settings to use the Okta OAuth2 endpoints and authorization parameters.
   - When a user logs in to your application, redirect them to the Okta OAuth2 authorize URL.
   - After the user authenticates with Okta, Okta will redirect them back to your application with an authorization code.

3. Implement OAuth2-based authentication and authorization in your application:
   - Exchange the authorization code received from Okta for an access token and refresh token.
   - Use the access token to authenticate the user within your application.
   - Authorize the user to access the appropriate resources and functionality within your application.
   - Refresh the access token as needed using the refresh token.

## Programming Details

### AWS Cognito

This example below shows how to authenticate a user using the `InitiateAuth` API, retrieve a list of users using the `ListUsers` API, create a new user using the `AdminCreateUser` API, disable a user using the `AdminDisableUser` API, create a new group using the `AdminCreateGroup` API, add newly created user to newly created group using `AdminAddUserToGroup` API, and disable an access token using the `AdminDisableUser` API.
```
using Amazon.CognitoIdentityProvider;
using Amazon.CognitoIdentityProvider.Model;
using System;
using System.Collections.Generic;

namespace CognitoExample
{
    class Program
    {
        static void Main(string[] args)
        {
            // Set up the AWS credentials and Cognito client
            var credentials = new Amazon.Runtime.BasicAWSCredentials("AccessKey", "SecretKey");
            var client = new AmazonCognitoIdentityProviderClient(credentials, Amazon.RegionEndpoint.USWest2);

            // Authenticate a user using the InitiateAuth API
            var initiateAuthRequest = new InitiateAuthRequest
            {
                AuthFlow = AuthFlowType.USER_PASSWORD_AUTH,
                ClientId = "AppClientId",
                AuthParameters = new Dictionary<string, string> { { "USERNAME", "username@example.com" }, { "PASSWORD", "password" } }
            };
            var initiateAuthResponse = client.InitiateAuth(initiateAuthRequest);
            var accessToken = initiateAuthResponse.AuthenticationResult.AccessToken;

            // Call the ListUsers API to retrieve a list of users in a user pool
            var listUsersRequest = new ListUsersRequest
            {
                UserPoolId = "UserPoolId"
            };
            var listUsersResponse = client.ListUsers(listUsersRequest);
            foreach (var user in listUsersResponse.Users)
            {
                Console.WriteLine($"Username: {user.Username}");
                Console.WriteLine($"Enabled: {user.Enabled}");
            }

            // Call the AdminCreateUser API to create a new user in a user pool
            var createUserRequest = new AdminCreateUserRequest
            {
                UserPoolId = "UserPoolId",
                Username = "newuser@example.com",
                UserAttributes = new List<AttributeType> { new AttributeType { Name = "email", Value = "newuser@example.com" } },
                TemporaryPassword = "TempPassword123",
                MessageAction = MessageActionType.SUPPRESS
            };
            var createUserResponse = client.AdminCreateUser(createUserRequest);

            // Call the AdminDisableUser API to disable a user in a user pool
            var disableUserRequest = new AdminDisableUserRequest
            {
                UserPoolId = "UserPoolId",
                Username = "username@example.com"
            };
            var disableUserResponse = client.AdminDisableUser(disableUserRequest);

            // Call the AdminCreateGroup API to create a new group in a user pool
            var createGroupRequest = new AdminCreateGroupRequest
            {
                UserPoolId = "UserPoolId",
                GroupName = "NewGroup",
                Description = "A new group"
            };
            var createGroupResponse = client.AdminCreateGroup(createGroupRequest);

            // Call the AdminAddUserToGroup API to add the newly created user to the newly created group
            var addUserToGroupRequest = new AdminAddUserToGroupRequest
            {
                UserPoolId = "UserPoolId",
                Username = "newuser@example.com",
                GroupName = "NewGroup"
            };
            var addUserToGroupResponse = client.AdminAddUserToGroup(addUserToGroupRequest);

            // Call the AdminDisableUser API to disable an access token for a user in a user pool
            var disableTokenRequest = new AdminDisableUserRequest
            {
                UserPoolId = "UserPoolId",
                Username = "username@example.com"
            };
            var disableTokenResponse = client.AdminDisableUser(disableTokenRequest);

            Console.WriteLine("Done.");
        }
    }
}
```


## Questions

### AWS Cognito

- How to handle organizations to allow their corresponding admins to manage their users?
  - Use different user pools or different groups in a pool?  Any financial impact between these two approaches? 
- What is Cognito **Advanced Security Features**?
- Support SAML2 SSO and only 50 MAU free with $0.015 MAU?
- What is Cognito Sync for?  Example of use case?
- 

### Okto & Auth0

- How to handle organizations since we have several thousands of organizations in our current application?
