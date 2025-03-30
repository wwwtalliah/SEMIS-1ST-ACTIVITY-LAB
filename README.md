# SEMIS-1ST-ACTIVITY-LAB
https://youtube.com/shorts/LFOlbTNaOuA?feature=shared

#include <iostream>
#include<string>

using namespace std;

int main()
{
    string word, next;
    cout<< "This is a dictionary of Psychological terms. Please type 'next' to run the program. ";
    cin>>next;
 
    cout<< "List of Terms:                                                  Anxiety                                                       Behaviorism                                                    Conformity                                                     Depression                                                     Empathy                                                        Locus of Control                                               Motivation                                                     Neuroplasticity                                                Operant Conditioning                                           Psychopathy                                                    Reciprocity                                                    Self-esteem";
           
    cin>> next;
    
    cout<< "Please choose a word to reveal its definition: ";
    cin>>word;
    if (word=="anxiety")
    {
        cout<<"A feeling of worry, nervousness, or unease, typically about an imminent event or something with an uncertain outcome ";
    }
    else if (word=="behaviorism")
    {
        cout<<"A theory of learning which states that all behaviors are acquired through conditioning, and that our responses to environmental stimuli shape our behavior.";
    }
    else if (word=="conformity")
    {
        cout<<"The act of matching attitudes, beliefs, and behaviors to group norms or societal expectations.";
    }
    else if (word=="depression")
    {
        cout<<"A mood disorder characterized by persistent feelings of sadness, hopelessness, and loss of interest in activities.";
    }
    else if (word=="empathy")
    {
        cout<<"The ability to understand and share the feelings of another.";
    }
    else if (word=="locus of control")
    {
        cout<<"The degree to which individuals believe they have control over the outcome of events in their lives.";
    }
    else if (word=="motivation")
    {
        cout<<"The process that initiates, guides, and sustains goal-oriented behavior.";
    }
    else if (word=="neuroplasticity")
    {
        cout<<"The ability of the brain to change and adapt as a result of experience.";
    }
    else if (word=="operant conditioning")
    {
        cout<<"A method of learning that occurs through rewards and punishments for behavior, which influences the likelihood of that behavior being repeated.";
    }
    else if (word=="psychopathy")
    {
        cout<<"A personality disorder characterized by persistent antisocial behavior, impaired empathy, and bold, disinhibited, and egotistical traits.";
    }
    else if (word=="reciprocity")
    {
        cout<<"The practice of exchanging things with others for mutual benefit.";
    }
    else if (word=="self-esteem")
    {
        cout<<"One's sense of self-worth or personal value.";
    }
   else
   {
    cout << "Sorry, the word '" << word << "' is not on the list.";
   }
      
    return 0;
}
